# dev-tools
Tools for dev stuff

## Check C/C++ version

```C
#if (__STDC_VERSION__ == 199409L)
	#pragma message ( "C94" )
#elif (__STDC_VERSION__ == 199901L)
	#pragma message ( "C99" )
#elif (__STDC_VERSION__ == 201112L)
	#pragma message ( "C11" )
#elif (__STDC_VERSION__ == 201710L)
	#pragma message ( "C18" )
#endif

#if (__cplusplus == 199711L)
	#pragma message ( "C++98" )
#elif (__cplusplus == 201103L)
	#pragma message ( "C++11" )
#elif (__cplusplus == 201402L)
	#pragma message ( "C++14" )
#elif (__cplusplus == 201703L)
	#pragma message ( "C++17" )
#endif
```
