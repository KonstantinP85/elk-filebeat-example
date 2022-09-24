# Simple usage ELK with filebeat

## Project init

#### Filter is a [ruby filter plagin](https://www.elastic.co/guide/en/logstash/current/plugins-filters-ruby.html)

#### Run docker containers:
`docker-compose up -d`

##### Wait 1 minute.

#### Open kibana [http://localhost:5601/]() 

#### Go to Analitics -> Discover -> Create Data View


![Снимок экрана от 2022-09-24 09-29-00](https://user-images.githubusercontent.com/74908254/192076923-3475355e-a6fe-4ffd-8794-bece5d8598d8.png)

#### For example:  name - "api_log" and Index pattern "api*"

![Снимок экрана от 2022-09-24 10-21-17](https://user-images.githubusercontent.com/74908254/192078316-0dae615a-cd98-4dad-a515-753d511e3bcc.png)

#### You can see the logs

![Снимок экрана от 2022-09-24 10-21-55](https://user-images.githubusercontent.com/74908254/192078438-b5b77416-aa82-4243-8d6c-ade9723128b0.png)

#### You can use the search

![Снимок экрана от 2022-09-24 10-22-15](https://user-images.githubusercontent.com/74908254/192078524-d56179a4-7602-45fd-8642-2a39bccc7353.png)
