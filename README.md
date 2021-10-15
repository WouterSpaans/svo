# svo

```
sudo apt install git ansible -y ; sudo ansible-pull -U https://github.com/WouterSpaans/svo.git
```

Get development branche
```
mkdir '/home/wouter/repos/SVO vakopleiding food'
git clone -b development https://caveroit.visualstudio.com/DefaultCollection/SVO%20vakopleiding%20food/_git/SVO%20vakopleiding%20food '/home/wouter/repos/SVO vakopleiding food'
```

Build/Run API
```
dotnet "build" "/home/wouter/repos/SVO vakopleiding food/SVOFood.ProductRecognition.API/SVOFood.ProductRecognition.API.csproj"
dotnet '/home/wouter/repos/SVO vakopleiding food/SVOFood.ProductRecognition.API/bin/Debug/net5.0/SVOFood.ProductRecognition.API.dll' --urls http://localhost:64880
```

Run Android App
```
cd '/home/wouter/repos/SVO vakopleiding food/SVOFood.ProductRecognition.App/'
npm install
tns run android
```
