
# MEMORY (ALLOC) (Intel-x64-i5-13420H Windows10-HomeSingle_25H2 TCC-0.9.24)

**Status:** __(2026/08/18) PERFECT!!!__

## Performance Results:

Compiled with (CMD): `tcc test.c && test.exe`

```c
malloc(16):
  total:   366.631 ms - average: 36.663 ns

ALLOC(16):
  total:   335.429 ms - average: 33.543 ns

-----------------------------
malloc(64):
  total:   363.867 ms - average: 36.387 ns

ALLOC(64):
  total:   347.681 ms - average: 34.768 ns

-----------------------------
malloc(256):
  total:   362.526 ms - average: 36.253 ns

ALLOC(256):
  total:   370.041 ms - average: 37.004 ns

-----------------------------
malloc(1024):
  total:   362.575 ms - average: 36.258 ns

ALLOC(1024):
  total:   401.842 ms - average: 40.184 ns

-----------------------------
malloc(4096):
  total:   362.518 ms - average: 36.252 ns

ALLOC(4096):
  total:   438.611 ms - average: 43.861 ns

-----------------------------
malloc(16384):
  total:   360.187 ms - average: 36.019 ns

ALLOC(16384):
  total:   440.744 ms - average: 44.074 ns

-----------------------------
malloc(80200):
  total:   1065.822 ms - average: 106.582 ns

ALLOC(80200):
  total:   443.374 ms - average: 44.337 ns

-----------------------------
malloc(580200):
  total:   45648.395 ms - average: 4564.839 ns

ALLOC(580200):
  total:   440.972 ms - average: 44.097 ns

-----------------------------
malloc(1000000):
  total:   51216.560 ms - average: 5121.656 ns

ALLOC(1000000):
  total:   440.307 ms - average: 44.031 ns

-----------------------------
```

----

Compiled with (CMD): `tcc -O0 test.c && test.exe`

```c
malloc(16):
  total:   367.824 ms - average: 36.782 ns

ALLOC(16):
  total:   334.402 ms - average: 33.440 ns

-----------------------------
malloc(64):
  total:   366.796 ms - average: 36.680 ns

ALLOC(64):
  total:   349.321 ms - average: 34.932 ns

-----------------------------
malloc(256):
  total:   366.318 ms - average: 36.632 ns

ALLOC(256):
  total:   368.549 ms - average: 36.855 ns

-----------------------------
malloc(1024):
  total:   362.410 ms - average: 36.241 ns

ALLOC(1024):
  total:   408.945 ms - average: 40.895 ns

-----------------------------
malloc(4096):
  total:   362.600 ms - average: 36.260 ns

ALLOC(4096):
  total:   442.246 ms - average: 44.225 ns

-----------------------------
malloc(16384):
  total:   360.648 ms - average: 36.065 ns

ALLOC(16384):
  total:   438.642 ms - average: 43.864 ns

-----------------------------
malloc(80200):
  total:   1071.530 ms - average: 107.153 ns

ALLOC(80200):
  total:   441.434 ms - average: 44.143 ns

-----------------------------
malloc(580200):
  total:   45713.797 ms - average: 4571.380 ns

ALLOC(580200):
  total:   441.541 ms - average: 44.154 ns

-----------------------------
malloc(1000000):
  total:   62652.252 ms - average: 6265.225 ns

ALLOC(1000000):
  total:   440.647 ms - average: 44.065 ns

-----------------------------
```

----

Compiled with (CMD): `tcc -O1 test.c && test.exe`

```c
malloc(16):
  total:   365.414 ms - average: 36.541 ns

ALLOC(16):
  total:   334.838 ms - average: 33.484 ns

-----------------------------
malloc(64):
  total:   367.763 ms - average: 36.776 ns

ALLOC(64):
  total:   347.116 ms - average: 34.712 ns

-----------------------------
malloc(256):
  total:   363.031 ms - average: 36.303 ns

ALLOC(256):
  total:   365.813 ms - average: 36.581 ns

-----------------------------
malloc(1024):
  total:   362.377 ms - average: 36.238 ns

ALLOC(1024):
  total:   414.352 ms - average: 41.435 ns

-----------------------------
malloc(4096):
  total:   549.670 ms - average: 54.967 ns

ALLOC(4096):
  total:   891.450 ms - average: 89.145 ns

-----------------------------
malloc(16384):
  total:   653.777 ms - average: 65.378 ns

ALLOC(16384):
  total:   894.713 ms - average: 89.471 ns

-----------------------------
malloc(80200):
  total:   2066.647 ms - average: 206.665 ns

ALLOC(80200):
  total:   903.908 ms - average: 90.391 ns

-----------------------------
malloc(580200):
  total:   86222.327 ms - average: 8622.233 ns

ALLOC(580200):
  total:   446.748 ms - average: 44.675 ns

-----------------------------
malloc(1000000):
  total:   51722.342 ms - average: 5172.234 ns

ALLOC(1000000):
  total:   441.181 ms - average: 44.118 ns

-----------------------------
```

----

Compiled with (CMD): `tcc -O2 test.c && test.exe`

```c
malloc(16):
  total:   379.055 ms - average: 37.906 ns

ALLOC(16):
  total:   342.878 ms - average: 34.288 ns

-----------------------------
malloc(64):
  total:   367.266 ms - average: 36.727 ns

ALLOC(64):
  total:   356.151 ms - average: 35.615 ns

-----------------------------
malloc(256):
  total:   366.993 ms - average: 36.699 ns

ALLOC(256):
  total:   368.202 ms - average: 36.820 ns

-----------------------------
malloc(1024):
  total:   361.566 ms - average: 36.157 ns

ALLOC(1024):
  total:   405.201 ms - average: 40.520 ns

-----------------------------
malloc(4096):
  total:   580.991 ms - average: 58.099 ns

ALLOC(4096):
  total:   903.574 ms - average: 90.357 ns

-----------------------------
malloc(16384):
  total:   666.104 ms - average: 66.610 ns

ALLOC(16384):
  total:   907.345 ms - average: 90.734 ns

-----------------------------
malloc(80200):
  total:   2066.540 ms - average: 206.654 ns

ALLOC(80200):
  total:   913.041 ms - average: 91.304 ns

-----------------------------
malloc(580200):
  total:   69731.656 ms - average: 6973.166 ns

ALLOC(580200):
  total:   439.225 ms - average: 43.923 ns

-----------------------------
malloc(1000000):
  total:   51858.786 ms - average: 5185.879 ns

ALLOC(1000000):
  total:   433.749 ms - average: 43.375 ns

-----------------------------
```

----

Compiled with (CMD): `tcc -O3 test.c && test.exe`

```c
malloc(16):
  total:   369.025 ms - average: 36.903 ns

ALLOC(16):
  total:   334.624 ms - average: 33.462 ns

-----------------------------
malloc(64):
  total:   370.792 ms - average: 37.079 ns

ALLOC(64):
  total:   350.563 ms - average: 35.056 ns

-----------------------------
malloc(256):
  total:   362.729 ms - average: 36.273 ns

ALLOC(256):
  total:   368.712 ms - average: 36.871 ns

-----------------------------
malloc(1024):
  total:   362.434 ms - average: 36.243 ns

ALLOC(1024):
  total:   404.473 ms - average: 40.447 ns

-----------------------------
malloc(4096):
  total:   360.910 ms - average: 36.091 ns

ALLOC(4096):
  total:   440.696 ms - average: 44.070 ns

-----------------------------
malloc(16384):
  total:   361.752 ms - average: 36.175 ns

ALLOC(16384):
  total:   439.530 ms - average: 43.953 ns

-----------------------------
malloc(80200):
  total:   1071.024 ms - average: 107.102 ns

ALLOC(80200):
  total:   443.542 ms - average: 44.354 ns

-----------------------------
malloc(580200):
  total:   79008.246 ms - average: 7900.825 ns

ALLOC(580200):
  total:   893.306 ms - average: 89.331 ns

-----------------------------
malloc(1000000):
  total:   75052.328 ms - average: 7505.233 ns

ALLOC(1000000):
  total:   440.485 ms - average: 44.048 ns

-----------------------------
```

## `test.c` Source Code:

```c
#include <stdio.h>
#include <stdlib.h>
#include <stdint.h>
#include <windows.h>

#define INCL_CMT_MEMORY
#include "CMT/CMT.H"

#define ITERATIONS 10000000

static uint64_t
	get_time_ns(void)
{
	static LARGE_INTEGER frequency;
	LARGE_INTEGER counter;

	if (frequency.QuadPart == 0)
		QueryPerformanceFrequency(&frequency);

	QueryPerformanceCounter(&counter);

	return (uint64_t)(
		(counter.QuadPart * 1000000000ULL) /
		frequency.QuadPart
	);
}

static void
	benchmark_malloc(size_t size)
{
	volatile void *ptr;
	uint64_t    start;
	uint64_t    end;
	size_t      i;
	uint64_t    elapsed;

	start = get_time_ns();

	for (i = 0; i < ITERATIONS; i++)
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
	elapsed = end - start;

	printf("malloc(%u):\n", (unsigned)size);
	printf("  total:   %.3f ms - ", (double)elapsed / 1000000.0);
	printf("average: %.3f ns\n\n",
		(double)elapsed / (double)ITERATIONS);
}

static void
	benchmark_alloc(size_t size)
{
	volatile void *ptr;
	uint64_t    start;
	uint64_t    end;
	size_t      i;
	uint64_t    elapsed;

	start = get_time_ns();

	for (i = 0; i < ITERATIONS; i++)
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
	elapsed = end - start;

	printf("ALLOC(%u):\n", (unsigned)size);
	printf("  total:   %.3f ms - ", (double)elapsed / 1000000.0);
	printf("average: %.3f ns\n\n",
		(double)elapsed / (double)ITERATIONS);
}

int
	main(void)
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

	size_t count;
	size_t i;

	count = sizeof(sizes) / sizeof(sizes[0]);

	for (i = 0; i < count; i++)
	{
		size_t size = sizes[i];

		benchmark_malloc(size);
		benchmark_alloc(size);

		printf("-----------------------------\n");
	}

	return 0;
}
```

## Issues / Bugs

----

