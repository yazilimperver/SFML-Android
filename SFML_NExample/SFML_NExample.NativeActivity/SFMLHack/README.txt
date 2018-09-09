We need to copy the headers because the android studio gradle build system doens't support "WHOLE_STATIC_LIB"
from the old build system yet. So these functions would get stripped (ANativeActivity_onCreate is the important
one during SFML Startup) if we do not add them directly. As soon as WHOLE_STATIC_LIB is supported, we
can delete this folder!