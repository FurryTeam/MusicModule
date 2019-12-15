worker: sh release.sh && java -jar musicbot.jar
release: sh release.sh
web: mv /app/target/JMusicBot-0.2.6-All.jar /app/musicbot.jar && cp /app/musicbot.jar /app/web/musicbot.jar && vendor/bin/heroku-php-apache2 web/
