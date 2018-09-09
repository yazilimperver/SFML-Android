# SFML-Android

This project includes SFML 2.5.0 source code and corresponding Visual Studio 2017 files that can be used to generate corresponding libraries on windows.
Currently, only X86 ABI is working. I could not resolve the problem with ARM which might be stemmed from my toolset, but I will check that out.
The example is also a little bit different from the official android example which is based on Gradle. I uses https://github.com/AlexAUT/SFML-AndroidStudio-Template.

## Getting Started

You can clone and build corresponding SFML library using visual studio.

### Prerequisites

Be careful about the tools as Android drop ant support do not forget to use previous ant tools. Check my post about this issue below.
http://www.yazilimperver.com/index.php/2018/08/29/vs-ndk-guncellemeleri/
