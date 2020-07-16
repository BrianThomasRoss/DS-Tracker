release: flask db upgrade
web: gunicorn ds_tracker.app:create_app\(\) -b 0.0.0.0:$PORT -w 3
