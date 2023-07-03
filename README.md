# cas-mail-api

# How to deploy service 
## Step1: Install dependencies
```shell script
pip3 install -r requirements.txt

pip3 install --upgrade protobuf
```

## Step2: Run 
```shell script
python3 startup.py
```

# How to build protobuf
## Step1:
```shell script
cd casmail/taskmanager/grpc
./clean.sh
./build.sh
```