web: gunicorn -w 4 -k uvicorn.workers.UvicornWorker code.main:blockchain --bind 0.0.0.0:${MYCHAIN_PORT:-5000}
