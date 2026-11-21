
1. ASGI (Asynchronous Server Gateway Interface) is a standard interface between Python asynchronous web servers, frameworks, and applications:
- ASGI is structured as an asynchronous Python callable that takes scope which stands for details about the specific connection, receive - the response it gets, and send - the payload it passes.
- This application uses an ASGI-based web server - Uvicorn to maintain the work of FastAPI.
- Starlette is a contemporary modern ASGI toolkit that allows builds and support FastAPI applications


