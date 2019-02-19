# Dayu
一款web应用指纹扫描工具。

Options:                                                                                                                                 
    -u A Domain or IP,or more Domain or IP use','separate.                                                                              
    -r The normal Domain or IP file path.                                                                                                
    -t Enter a number of threads, The default threads is 50.
    -p Enter a http-proxy port, The default port is 80.                                                                                  
    -s Set the access protocol, The default protocol is http.(http、https)                                                               
    -h See To help illustrate.                                                                                                            
    -o Output String to The normal local file path.                                                                                       
    -m Change the probe model, The default model is 1.(1: get fast probe to result 2: get high hit rate fingerprint to result 3: get all fingerprints to results)                                                                                                                  
    --http-request Set the custom request url path.                                                                                       
    --http-response Set the custom response Context word.                                                                                
Example: java -jar Dayu.jar -u www.discuz.net -t 80                                                                                       
Example: java -jar Dayu.jar -u www.discuz.net -s https -p 8080                                                                            
Example: java -jar Dayu.jar -r d:\ip.txt -m 3                                                                                             
Example: java -jar Dayu.jar -u www.discuz.net --http-request /robots.txt --http-response Discuz                                           
 
注：会在D盘下生成日志文件，后续可能修改。目前限于windows主机下运行。
