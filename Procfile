web: cd code && gunicorn -w 4 -k uvicorn.workers.UvicornWorker main:blockchain --bind 0.0.0.0:${MYCHAIN_PORT:-5000}
