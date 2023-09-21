web: gunicorn -w 4 -k uvicorn.workers.UvicornWorker code.main:app --bind 0.0.0.0:${MYCHAIN_PORT:-5000}
