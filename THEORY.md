
1. ASGI (Asynchronous Server Gateway Interface) is a standard interface between Python asynchronous web servers, frameworks, and applications:
- ASGI is structured as an asynchronous Python callable that takes scope which stands for details about the specific connection, receive - the response it gets, and send - the payload it passes.
- This application uses an ASGI-based web server - Uvicorn to maintain the work of FastAPI.
- Starlette is a contemporary modern ASGI toolkit that allows builds and support FastAPI applications

2. Docker is a software responsible for packaging your app dependencies into a single and standalone container that can be launched with one command. 
 - The container is an isolated box with its own file system that runs independently on any operational system.
 - A Docker Image is an immutable blueprint that packages a needed environment such as code, libraries, dependencies and Linux to run the container. 


