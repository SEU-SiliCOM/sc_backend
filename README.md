# sc_backend
项目后端

## 运行
gunicorn -c gunicorn.py -k uvicorn.workers.UvicornWorker backend.asgi:application
