## Ejemplos de Logstash 

** Objetivos **

- Grok
- Oficial Repos ()

    git@github.com:elastic/examples.git 
    https://github.com/elastic/examples#quick-start

    Tutorial:
    https://www.elastic.co/blog/building-cloud-sandbox-with-sample-data-v2



## RESOURCES: (PC PABLO)

    - /Users/pabloinchausti/Desktop/DevOps/code/github/_Public/elastic
    

## COMANDOS:


## PASO #02


/opt/logstash/bin/logstash -e 'input { stdin { } } output { stdout {} }'

echo "Hola Logstash" | /opt/logstash/bin/logstash -e 'input { stdin { } } output { stdout {} }'

sudo ./filebeat -e -c filebeat.yml -d "publish"

/opt/logstash/bin/logstash -f ${ELK_STACK_TALK_HOME}/Filebeat/logstash-filebeat.conf


