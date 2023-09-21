web: gunicorn -w 4 k uvicorn.workers.UvicornWorker main:blockchain --host=0.0.0.0 --port=${MYCHAIN_PORT:-5000}
