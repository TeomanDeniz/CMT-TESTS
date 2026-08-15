
# TESTS - MEMORY (Intel-x64-i5-13420H WSL_ArchLinux-rolling GCC-16.1.1_Linux)

**Status:** __(2026/08/15) Pass__

## Performance Results:

Compiled with (BASH): `gcc test.c && ./a.out`

```c
malloc(16):
  total:   43.829 ms - average: 4.383 ns

ALLOC(16):
  total:   91.405 ms - average: 9.140 ns

-----------------------------
malloc(64):
  total:   45.239 ms - average: 4.524 ns

ALLOC(64):
  total:   88.093 ms - average: 8.809 ns

-----------------------------
malloc(256):
  total:   44.427 ms - average: 4.443 ns

ALLOC(256):
  total:   90.949 ms - average: 9.095 ns

-----------------------------
malloc(1024):
  total:   44.117 ms - average: 4.412 ns

ALLOC(1024):
  total:   173.609 ms - average: 17.361 ns

-----------------------------
malloc(4096):
  total:   128.734 ms - average: 12.873 ns

ALLOC(4096):
  total:   181.310 ms - average: 18.131 ns

-----------------------------
malloc(16384):
  total:   132.269 ms - average: 13.227 ns

ALLOC(16384):
  total:   181.312 ms - average: 18.131 ns

-----------------------------
malloc(80200):
  total:   126.194 ms - average: 12.619 ns

ALLOC(80200):
  total:   181.584 ms - average: 18.158 ns

-----------------------------
malloc(580200):
  total:   127.900 ms - average: 12.790 ns

ALLOC(580200):
  total:   178.812 ms - average: 17.881 ns

-----------------------------
malloc(1000000):
  total:   126.966 ms - average: 12.697 ns

ALLOC(1000000):
  total:   181.620 ms - average: 18.162 ns

-----------------------------
```

----

Compiled with (BASH): `gcc test.c -O0 && ./a.out`

```c
malloc(16):
  total:   44.932 ms - average: 4.493 ns

ALLOC(16):
  total:   89.443 ms - average: 8.944 ns

-----------------------------
malloc(64):
  total:   44.182 ms - average: 4.418 ns

ALLOC(64):
  total:   90.282 ms - average: 9.028 ns

-----------------------------
malloc(256):
  total:   44.552 ms - average: 4.455 ns

ALLOC(256):
  total:   92.024 ms - average: 9.202 ns

-----------------------------
malloc(1024):
  total:   44.848 ms - average: 4.485 ns

ALLOC(1024):
  total:   178.320 ms - average: 17.832 ns

-----------------------------
malloc(4096):
  total:   125.545 ms - average: 12.554 ns

ALLOC(4096):
  total:   179.499 ms - average: 17.950 ns

-----------------------------
malloc(16384):
  total:   126.918 ms - average: 12.692 ns

ALLOC(16384):
  total:   173.698 ms - average: 17.370 ns

-----------------------------
malloc(80200):
  total:   127.145 ms - average: 12.715 ns

ALLOC(80200):
  total:   174.826 ms - average: 17.483 ns

-----------------------------
malloc(580200):
  total:   125.321 ms - average: 12.532 ns

ALLOC(580200):
  total:   183.274 ms - average: 18.327 ns

-----------------------------
malloc(1000000):
  total:   123.345 ms - average: 12.335 ns

ALLOC(1000000):
  total:   172.206 ms - average: 17.221 ns

-----------------------------
```

----

Compiled with (BASH): `gcc test.c -O1 && ./a.out`

```c
malloc(16):
  total:   2.260 ms - average: 0.226 ns

ALLOC(16):
  total:   47.975 ms - average: 4.797 ns

-----------------------------
malloc(64):
  total:   2.737 ms - average: 0.274 ns

ALLOC(64):
  total:   49.293 ms - average: 4.929 ns

-----------------------------
malloc(256):
  total:   2.268 ms - average: 0.227 ns

ALLOC(256):
  total:   47.952 ms - average: 4.795 ns

-----------------------------
malloc(1024):
  total:   2.265 ms - average: 0.227 ns

ALLOC(1024):
  total:   165.903 ms - average: 16.590 ns

-----------------------------
malloc(4096):
  total:   2.414 ms - average: 0.241 ns

ALLOC(4096):
  total:   163.461 ms - average: 16.346 ns

-----------------------------
malloc(16384):
  total:   2.315 ms - average: 0.232 ns

ALLOC(16384):
  total:   162.070 ms - average: 16.207 ns

-----------------------------
malloc(80200):
  total:   2.512 ms - average: 0.251 ns

ALLOC(80200):
  total:   162.068 ms - average: 16.207 ns

-----------------------------
malloc(580200):
  total:   2.313 ms - average: 0.231 ns

ALLOC(580200):
  total:   158.866 ms - average: 15.887 ns

-----------------------------
malloc(1000000):
  total:   2.948 ms - average: 0.295 ns

ALLOC(1000000):
  total:   160.290 ms - average: 16.029 ns

-----------------------------
```

----

Compiled with (BASH): `gcc test.c -O2 && ./a.out`

```c
malloc(16):
  total:   0.000 ms - average: 0.000 ns

ALLOC(16):
  total:   51.803 ms - average: 5.180 ns

-----------------------------
malloc(64):
  total:   0.000 ms - average: 0.000 ns

ALLOC(64):
  total:   52.526 ms - average: 5.253 ns

-----------------------------
malloc(256):
  total:   0.000 ms - average: 0.000 ns

ALLOC(256):
  total:   53.147 ms - average: 5.315 ns

-----------------------------
malloc(1024):
  total:   0.000 ms - average: 0.000 ns

ALLOC(1024):
  total:   159.214 ms - average: 15.921 ns

-----------------------------
malloc(4096):
  total:   0.000 ms - average: 0.000 ns

ALLOC(4096):
  total:   153.699 ms - average: 15.370 ns

-----------------------------
malloc(16384):
  total:   0.000 ms - average: 0.000 ns

ALLOC(16384):
  total:   155.724 ms - average: 15.572 ns

-----------------------------
malloc(80200):
  total:   0.000 ms - average: 0.000 ns

ALLOC(80200):
  total:   156.462 ms - average: 15.646 ns

-----------------------------
malloc(580200):
  total:   0.000 ms - average: 0.000 ns

ALLOC(580200):
  total:   150.479 ms - average: 15.048 ns

-----------------------------
malloc(1000000):
  total:   0.000 ms - average: 0.000 ns

ALLOC(1000000):
  total:   159.463 ms - average: 15.946 ns

-----------------------------
```

----

Compiled with (BASH): `gcc test.c -O3 && ./a.out`

```c
malloc(16):
  total:   0.000 ms - average: 0.000 ns

ALLOC(16):
  total:   50.641 ms - average: 5.064 ns

-----------------------------
malloc(64):
  total:   0.000 ms - average: 0.000 ns

ALLOC(64):
  total:   51.634 ms - average: 5.163 ns

-----------------------------
malloc(256):
  total:   0.000 ms - average: 0.000 ns

ALLOC(256):
  total:   50.749 ms - average: 5.075 ns

-----------------------------
malloc(1024):
  total:   0.000 ms - average: 0.000 ns

ALLOC(1024):
  total:   147.710 ms - average: 14.771 ns

-----------------------------
malloc(4096):
  total:   0.000 ms - average: 0.000 ns

ALLOC(4096):
  total:   151.830 ms - average: 15.183 ns

-----------------------------
malloc(16384):
  total:   0.000 ms - average: 0.000 ns

ALLOC(16384):
  total:   153.395 ms - average: 15.340 ns

-----------------------------
malloc(80200):
  total:   0.000 ms - average: 0.000 ns

ALLOC(80200):
  total:   147.776 ms - average: 14.778 ns

-----------------------------
malloc(580200):
  total:   0.000 ms - average: 0.000 ns

ALLOC(580200):
  total:   142.068 ms - average: 14.207 ns

-----------------------------
malloc(1000000):
  total:   0.000 ms - average: 0.000 ns

ALLOC(1000000):
  total:   142.955 ms - average: 14.295 ns

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
   * Really slow compared to `malloc`

----

