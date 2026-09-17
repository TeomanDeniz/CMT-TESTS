
# MEMORY (ALLOC) (Intel-x64-i5-13420H WSL_ArchLinux-rolling TCC-0.9.28rc)

**Status:** __(2026/08/18) Pass__

## Performance Results:

Compiled with (BASH): `tcc test.c && ./a.out`

```c
malloc(16):
  total:   43.189 ms - average: 4.319 ns

ALLOC(16):
  total:   103.696 ms - average: 10.370 ns

-----------------------------
malloc(64):
  total:   43.083 ms - average: 4.308 ns

ALLOC(64):
  total:   102.333 ms - average: 10.233 ns

-----------------------------
malloc(256):
  total:   43.757 ms - average: 4.376 ns

ALLOC(256):
  total:   103.527 ms - average: 10.353 ns

-----------------------------
malloc(1024):
  total:   44.177 ms - average: 4.418 ns

ALLOC(1024):
  total:   105.121 ms - average: 10.512 ns

-----------------------------
malloc(4096):
  total:   135.260 ms - average: 13.526 ns

ALLOC(4096):
  total:   198.245 ms - average: 19.825 ns

-----------------------------
malloc(16384):
  total:   148.022 ms - average: 14.802 ns

ALLOC(16384):
  total:   198.287 ms - average: 19.829 ns

-----------------------------
malloc(80200):
  total:   137.537 ms - average: 13.754 ns

ALLOC(80200):
  total:   193.604 ms - average: 19.360 ns

-----------------------------
malloc(580200):
  total:   129.592 ms - average: 12.959 ns

ALLOC(580200):
  total:   199.217 ms - average: 19.922 ns

-----------------------------
malloc(1000000):
  total:   134.512 ms - average: 13.451 ns

ALLOC(1000000):
  total:   189.079 ms - average: 18.908 ns

-----------------------------
```

----

Compiled with (BASH): `tcc test.c -O0 && ./a.out`

```c
malloc(16):
  total:   43.465 ms - average: 4.346 ns

ALLOC(16):
  total:   103.306 ms - average: 10.331 ns

-----------------------------
malloc(64):
  total:   43.345 ms - average: 4.334 ns

ALLOC(64):
  total:   104.454 ms - average: 10.445 ns

-----------------------------
malloc(256):
  total:   43.921 ms - average: 4.392 ns

ALLOC(256):
  total:   102.945 ms - average: 10.294 ns

-----------------------------
malloc(1024):
  total:   44.357 ms - average: 4.436 ns

ALLOC(1024):
  total:   104.848 ms - average: 10.485 ns

-----------------------------
malloc(4096):
  total:   131.843 ms - average: 13.184 ns

ALLOC(4096):
  total:   200.693 ms - average: 20.069 ns

-----------------------------
malloc(16384):
  total:   137.085 ms - average: 13.708 ns

ALLOC(16384):
  total:   192.948 ms - average: 19.295 ns

-----------------------------
malloc(80200):
  total:   137.643 ms - average: 13.764 ns

ALLOC(80200):
  total:   193.834 ms - average: 19.383 ns

-----------------------------
malloc(580200):
  total:   128.509 ms - average: 12.851 ns

ALLOC(580200):
  total:   190.122 ms - average: 19.012 ns

-----------------------------
malloc(1000000):
  total:   130.071 ms - average: 13.007 ns

ALLOC(1000000):
  total:   195.005 ms - average: 19.500 ns

-----------------------------
```

----

Compiled with (BASH): `tcc test.c -O1 && ./a.out`

```c
malloc(16):
  total:   43.428 ms - average: 4.343 ns

ALLOC(16):
  total:   102.719 ms - average: 10.272 ns

-----------------------------
malloc(64):
  total:   43.296 ms - average: 4.330 ns

ALLOC(64):
  total:   103.159 ms - average: 10.316 ns

-----------------------------
malloc(256):
  total:   45.459 ms - average: 4.546 ns

ALLOC(256):
  total:   105.020 ms - average: 10.502 ns

-----------------------------
malloc(1024):
  total:   43.218 ms - average: 4.322 ns

ALLOC(1024):
  total:   102.809 ms - average: 10.281 ns

-----------------------------
malloc(4096):
  total:   133.102 ms - average: 13.310 ns

ALLOC(4096):
  total:   203.130 ms - average: 20.313 ns

-----------------------------
malloc(16384):
  total:   144.343 ms - average: 14.434 ns

ALLOC(16384):
  total:   205.460 ms - average: 20.546 ns

-----------------------------
malloc(80200):
  total:   133.032 ms - average: 13.303 ns

ALLOC(80200):
  total:   192.894 ms - average: 19.289 ns

-----------------------------
malloc(580200):
  total:   129.630 ms - average: 12.963 ns

ALLOC(580200):
  total:   191.404 ms - average: 19.140 ns

-----------------------------
malloc(1000000):
  total:   137.335 ms - average: 13.733 ns

ALLOC(1000000):
  total:   193.692 ms - average: 19.369 ns

-----------------------------
```

----

Compiled with (BASH): `tcc test.c -O2 && ./a.out`

```c
malloc(16):
  total:   43.317 ms - average: 4.332 ns

ALLOC(16):
  total:   102.812 ms - average: 10.281 ns

-----------------------------
malloc(64):
  total:   42.997 ms - average: 4.300 ns

ALLOC(64):
  total:   103.055 ms - average: 10.306 ns

-----------------------------
malloc(256):
  total:   43.595 ms - average: 4.359 ns

ALLOC(256):
  total:   104.644 ms - average: 10.464 ns

-----------------------------
malloc(1024):
  total:   43.058 ms - average: 4.306 ns

ALLOC(1024):
  total:   106.267 ms - average: 10.627 ns

-----------------------------
malloc(4096):
  total:   139.330 ms - average: 13.933 ns

ALLOC(4096):
  total:   207.137 ms - average: 20.714 ns

-----------------------------
malloc(16384):
  total:   140.970 ms - average: 14.097 ns

ALLOC(16384):
  total:   213.107 ms - average: 21.311 ns

-----------------------------
malloc(80200):
  total:   138.674 ms - average: 13.867 ns

ALLOC(80200):
  total:   197.757 ms - average: 19.776 ns

-----------------------------
malloc(580200):
  total:   133.587 ms - average: 13.359 ns

ALLOC(580200):
  total:   194.232 ms - average: 19.423 ns

-----------------------------
malloc(1000000):
  total:   135.479 ms - average: 13.548 ns

ALLOC(1000000):
  total:   196.637 ms - average: 19.664 ns

-----------------------------
```

----

Compiled with (BASH): `tcc test.c -O3 && ./a.out`

```c
malloc(16):
  total:   43.557 ms - average: 4.356 ns

ALLOC(16):
  total:   102.455 ms - average: 10.245 ns

-----------------------------
malloc(64):
  total:   43.523 ms - average: 4.352 ns

ALLOC(64):
  total:   105.217 ms - average: 10.522 ns

-----------------------------
malloc(256):
  total:   43.143 ms - average: 4.314 ns

ALLOC(256):
  total:   102.682 ms - average: 10.268 ns

-----------------------------
malloc(1024):
  total:   43.569 ms - average: 4.357 ns

ALLOC(1024):
  total:   103.094 ms - average: 10.309 ns

-----------------------------
malloc(4096):
  total:   137.497 ms - average: 13.750 ns

ALLOC(4096):
  total:   206.729 ms - average: 20.673 ns

-----------------------------
malloc(16384):
  total:   138.219 ms - average: 13.822 ns

ALLOC(16384):
  total:   202.169 ms - average: 20.217 ns

-----------------------------
malloc(80200):
  total:   140.805 ms - average: 14.080 ns

ALLOC(80200):
  total:   195.621 ms - average: 19.562 ns

-----------------------------
malloc(580200):
  total:   131.430 ms - average: 13.143 ns

ALLOC(580200):
  total:   194.837 ms - average: 19.484 ns

-----------------------------
malloc(1000000):
  total:   133.175 ms - average: 13.318 ns

ALLOC(1000000):
  total:   194.628 ms - average: 19.463 ns

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

 *  (2026/08/18) - (Still Present)
   * Really slow compared to `malloc`

----

