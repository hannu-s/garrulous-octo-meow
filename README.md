# garrulous-octo-meow
LasLib visual studio 2015

From: [LAStools repository](https://github.com/LAStools/LAStools/tree/master/LASlib)

### To start in VS2015:

* Project properties -> Configuration properties -> General -> Character Set -> **NOT SET**
* Project properties -> Configuration properties -> C/C++ -> Additional Include Directories -> **[Proj dir]\inc**
* Project properties -> Configuration properties -> C/C++ -> Preprocessor -> Preprocessor Definitions -> **_CRT_SECURE_NO_DEPRECATE**  
**_SILENCE_STDEXT_HASH_DEPRECATION_WARNINGS**  
**_CRT_NONSTDC_NO_DEPRECATE**
* Add int main(int argc, char *argv[])

Note that laszip_dll.cpp has partly commented out. Starting from line 3138.

