web: uwsgi --ini=uwsgi.ini --http=0.0.0.0:$PORT
worker: sentry --config=config/ run worker --loglevel=INFO
beat: sentry --config=config/ run cron --loglevel=INFO
release: sentry --config=config/ upgrade --noinput
