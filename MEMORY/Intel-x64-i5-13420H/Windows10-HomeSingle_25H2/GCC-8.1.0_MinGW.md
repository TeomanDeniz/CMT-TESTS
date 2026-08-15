
# TESTS - MEMORY (Intel-x64-i5-13420H Windows10-HomeSingle_25H2 GCC-8.1.0_MinGW)

**Status:** __(2026/08/15) Pass__

## Performance Results:

Compiled with (CMD): `gcc test.c && a.exe`

```c
malloc(16):
  total:   251.127 ms - average: 25.113 ns

ALLOC(16):
  total:   333.178 ms - average: 33.318 ns

-----------------------------
malloc(64):
  total:   251.548 ms - average: 25.155 ns

ALLOC(64):
  total:   339.164 ms - average: 33.916 ns

-----------------------------
malloc(256):
  total:   247.543 ms - average: 24.754 ns

ALLOC(256):
  total:   342.563 ms - average: 34.256 ns

-----------------------------
malloc(1024):
  total:   246.637 ms - average: 24.664 ns

ALLOC(1024):
  total:   349.801 ms - average: 34.980 ns

-----------------------------
malloc(4096):
  total:   247.831 ms - average: 24.783 ns

ALLOC(4096):
  total:   363.068 ms - average: 36.307 ns

-----------------------------
malloc(16384):
  total:   247.741 ms - average: 24.774 ns

ALLOC(16384):
  total:   363.565 ms - average: 36.357 ns

-----------------------------
malloc(80200):
  total:   837.075 ms - average: 83.708 ns

ALLOC(80200):
  total:   363.894 ms - average: 36.389 ns

-----------------------------
malloc(580200):
  total:   838.740 ms - average: 83.874 ns

ALLOC(580200):
  total:   364.522 ms - average: 36.452 ns

-----------------------------
malloc(1000000):
  total:   838.865 ms - average: 83.886 ns

ALLOC(1000000):
  total:   364.372 ms - average: 36.437 ns

-----------------------------
```

----

Compiled with (CMD): `gcc test.c -O0 && a.exe`

```c
malloc(16):
  total:   248.830 ms - average: 24.883 ns

ALLOC(16):
  total:   334.964 ms - average: 33.496 ns

-----------------------------
malloc(64):
  total:   251.338 ms - average: 25.134 ns

ALLOC(64):
  total:   343.623 ms - average: 34.362 ns

-----------------------------
malloc(256):
  total:   251.291 ms - average: 25.129 ns

ALLOC(256):
  total:   346.558 ms - average: 34.656 ns

-----------------------------
malloc(1024):
  total:   247.723 ms - average: 24.772 ns

ALLOC(1024):
  total:   350.471 ms - average: 35.047 ns

-----------------------------
malloc(4096):
  total:   248.885 ms - average: 24.889 ns

ALLOC(4096):
  total:   363.269 ms - average: 36.327 ns

-----------------------------
malloc(16384):
  total:   247.016 ms - average: 24.702 ns

ALLOC(16384):
  total:   366.944 ms - average: 36.694 ns

-----------------------------
malloc(80200):
  total:   840.782 ms - average: 84.078 ns

ALLOC(80200):
  total:   364.830 ms - average: 36.483 ns

-----------------------------
malloc(580200):
  total:   842.536 ms - average: 84.254 ns

ALLOC(580200):
  total:   364.248 ms - average: 36.425 ns

-----------------------------
malloc(1000000):
  total:   841.239 ms - average: 84.124 ns

ALLOC(1000000):
  total:   366.042 ms - average: 36.604 ns

-----------------------------
```

----

Compiled with (CMD): `gcc test.c -O1 && a.exe`

```c
malloc(16):
  total:   253.103 ms - average: 25.310 ns

ALLOC(16):
  total:   287.189 ms - average: 28.719 ns

-----------------------------
malloc(64):
  total:   250.938 ms - average: 25.094 ns

ALLOC(64):
  total:   287.919 ms - average: 28.792 ns

-----------------------------
malloc(256):
  total:   251.556 ms - average: 25.156 ns

ALLOC(256):
  total:   282.820 ms - average: 28.282 ns

-----------------------------
malloc(1024):
  total:   249.705 ms - average: 24.971 ns

ALLOC(1024):
  total:   282.463 ms - average: 28.246 ns

-----------------------------
malloc(4096):
  total:   249.438 ms - average: 24.944 ns

ALLOC(4096):
  total:   296.700 ms - average: 29.670 ns

-----------------------------
malloc(16384):
  total:   250.191 ms - average: 25.019 ns

ALLOC(16384):
  total:   297.842 ms - average: 29.784 ns

-----------------------------
malloc(80200):
  total:   837.168 ms - average: 83.717 ns

ALLOC(80200):
  total:   298.418 ms - average: 29.842 ns

-----------------------------
malloc(580200):
  total:   838.537 ms - average: 83.854 ns

ALLOC(580200):
  total:   296.688 ms - average: 29.669 ns

-----------------------------
malloc(1000000):
  total:   839.134 ms - average: 83.913 ns

ALLOC(1000000):
  total:   296.131 ms - average: 29.613 ns

-----------------------------
```

----

Compiled with (CMD): `gcc test.c -O2 && a.exe`

```c
malloc(16):
  total:   253.725 ms - average: 25.373 ns

ALLOC(16):
  total:   311.613 ms - average: 31.161 ns

-----------------------------
malloc(64):
  total:   248.301 ms - average: 24.830 ns

ALLOC(64):
  total:   320.079 ms - average: 32.008 ns

-----------------------------
malloc(256):
  total:   252.757 ms - average: 25.276 ns

ALLOC(256):
  total:   316.957 ms - average: 31.696 ns

-----------------------------
malloc(1024):
  total:   249.504 ms - average: 24.950 ns

ALLOC(1024):
  total:   316.806 ms - average: 31.681 ns

-----------------------------
malloc(4096):
  total:   248.241 ms - average: 24.824 ns

ALLOC(4096):
  total:   332.350 ms - average: 33.235 ns

-----------------------------
malloc(16384):
  total:   247.605 ms - average: 24.760 ns

ALLOC(16384):
  total:   333.954 ms - average: 33.395 ns

-----------------------------
malloc(80200):
  total:   842.971 ms - average: 84.297 ns

ALLOC(80200):
  total:   330.658 ms - average: 33.066 ns

-----------------------------
malloc(580200):
  total:   841.733 ms - average: 84.173 ns

ALLOC(580200):
  total:   329.615 ms - average: 32.961 ns

-----------------------------
malloc(1000000):
  total:   842.765 ms - average: 84.276 ns

ALLOC(1000000):
  total:   336.416 ms - average: 33.642 ns

-----------------------------
```

----

Compiled with (CMD): `gcc test.c -O3 && a.exe`

```c
malloc(16):
  total:   251.035 ms - average: 25.104 ns

ALLOC(16):
  total:   309.628 ms - average: 30.963 ns

-----------------------------
malloc(64):
  total:   251.362 ms - average: 25.136 ns

ALLOC(64):
  total:   322.183 ms - average: 32.218 ns

-----------------------------
malloc(256):
  total:   251.762 ms - average: 25.176 ns

ALLOC(256):
  total:   316.401 ms - average: 31.640 ns

-----------------------------
malloc(1024):
  total:   248.666 ms - average: 24.867 ns

ALLOC(1024):
  total:   319.359 ms - average: 31.936 ns

-----------------------------
malloc(4096):
  total:   248.689 ms - average: 24.869 ns

ALLOC(4096):
  total:   332.078 ms - average: 33.208 ns

-----------------------------
malloc(16384):
  total:   246.293 ms - average: 24.629 ns

ALLOC(16384):
  total:   334.715 ms - average: 33.471 ns

-----------------------------
malloc(80200):
  total:   840.514 ms - average: 84.051 ns

ALLOC(80200):
  total:   330.926 ms - average: 33.093 ns

-----------------------------
malloc(580200):
  total:   839.521 ms - average: 83.952 ns

ALLOC(580200):
  total:   329.715 ms - average: 32.971 ns

-----------------------------
malloc(1000000):
  total:   849.857 ms - average: 84.986 ns

ALLOC(1000000):
  total:   331.361 ms - average: 33.136 ns

-----------------------------
```

## `test.c` Source Code:

```c
#include <stdio.h>
#include <stdlib.h>
#include <stdint.h>
#include <time.h>

#define INCL_CMT_MEMORY
#include "CMT/CMT.H"

#define ITERATIONS 10000000 // 10M

static uint64_t
	get_time_ns(void)
{
	struct timespec	ts;

	clock_gettime(CLOCK_MONOTONIC, &ts);

	return ((uint64_t)ts.tv_sec * 1000000000ULL + (uint64_t)ts.tv_nsec);
}

static void
	benchmark_malloc(size_t size)
{
	volatile void	*ptr;
	uint64_t		start;
	uint64_t		end;

	start = get_time_ns();

	for (size_t i = 0; i < ITERATIONS; i++)
	{
		ptr = malloc(size);

		if (!ptr)
		{
			fprintf(stderr, "(malloc) failed\n");
			exit(EXIT_FAILURE);
		}

		free((void *)ptr);
	}

	end = get_time_ns();

	printf("malloc(%zu):\n", size);
	printf("  total:   %.3f ms - ", (end - start) / 1e6);
	printf("average: %.3f ns\n\n", (double)(end - start) / ITERATIONS);
}

static void
	benchmark_alloc(size_t size)
{
	volatile void	*ptr;
	uint64_t		start;
	uint64_t		end;

	start = get_time_ns();

	for (size_t i = 0; i < ITERATIONS; i++)
	{
		ptr = ALLOC(size);

		if (!ptr)
		{
			fprintf(stderr, "(ALLOC) failed\n");
			exit(EXIT_FAILURE);
		}

		FREE((void *)ptr);
	}

	end = get_time_ns();

	printf("ALLOC(%zu):\n", size);
	printf("  total:   %.3f ms - ", (end - start) / 1e6);
	printf("average: %.3f ns\n\n", (double)(end - start) / ITERATIONS);
}

int main(void)
{
	size_t sizes[] = {
		16,
		64,
		256,
		1024,
		4096,
		16384,
		80200,
		580200,
		1000000
	};

	size_t	count = sizeof(sizes) / sizeof(sizes[0]);

	for (size_t i = 0; i < count; i++)
	{
		size_t size = sizes[i];

		benchmark_malloc(size);
		benchmark_alloc(size);

		printf("-----------------------------\n");
	}

	return (0);
}
```

## Issues / Bugs

 *  (2026/08/15) - (Still Present)
   * In value 16384 or smaller, it works slower than `malloc`

----

