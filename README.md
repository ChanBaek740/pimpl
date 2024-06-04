# pimpl
pimpl idiom example

参考文章：[《编译防火墙——C++的Pimpl惯用法解析》](https://leehao.blog.csdn.net/article/details/47610309)


## windows【MinGW环境】中用cmake 编译
### 编译
mkdir build  
cd .\build\  
cmake -G"MinGW Makefiles" ..  
cd ..  
cmake --build build  
cmake --build build --target test_impl  
./build/test_impl.exe  

### 编译
mkdir build  
cmake -E chdir build cmake -G"MinGW Makefiles" ..  
cmake --build build  
cmake --build build --target test_impl  
./build/test_impl.exe  


```shell
PS E:\00_luawang\03_GitRepo_luwang\pimpl2> ./build/test_impl.exe
print from BookImpl
PS E:\00_luawang\03_GitRepo_luwang\pimpl2> 
```