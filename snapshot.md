<h1 align="center"> Humanode </h1>

<h1 align="center">

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/91562185/313867169-7ed59118-10e8-4601-bfc1-9de06b67e6b7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241206%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241206T085946Z&X-Amz-Expires=300&X-Amz-Signature=e71733c7888c6c400d6555c1101baac7b317fae8e8ad2ea4cf21906356942147&X-Amz-SignedHeaders=host)

</h1>

### New Block
```
rm -rf ~/.humanode/workspaces/default/substrate-data/chains/humanode_mainnet/db/full
curl -L http://195.26.247.253:81/full.tar.lz4 | lz4 -dc - | tar -xf - -C ~/.humanode/workspaces/default/substrate-data/chains/humanode_mainnet/db/
```
