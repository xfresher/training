```sh
cd /var/www/app/python/helloworld

# Generate gRPC code
python -m grpc_tools.protoc -I../../protos --python_out=. --pyi_out=. --grpc_python_out=. ../../protos/helloworld.proto

# Run the server
python greeter_server.py

# Run the client
python greeter_client.py
```
