
# MEMORY (ALLOC) (Intel-x64-i5-13420H WSL_Ubuntu-22.04.5_LTS GCC-11.4.0)

**Status:** __(2026/08/15) Pass__

## Performance Results:

Compiled with (BASH): `gcc test.c && ./a.out`

```c
malloc(16):
  total:   65.483 ms - average: 6.548 ns

ALLOC(16):
  total:   110.051 ms - average: 11.005 ns

-----------------------------
malloc(64):
  total:   66.300 ms - average: 6.630 ns

ALLOC(64):
  total:   111.890 ms - average: 11.189 ns

-----------------------------
malloc(256):
  total:   64.024 ms - average: 6.402 ns

ALLOC(256):
  total:   110.538 ms - average: 11.054 ns

-----------------------------
malloc(1024):
  total:   65.837 ms - average: 6.584 ns

ALLOC(1024):
  total:   196.329 ms - average: 19.633 ns

-----------------------------
malloc(4096):
  total:   146.631 ms - average: 14.663 ns

ALLOC(4096):
  total:   197.051 ms - average: 19.705 ns

-----------------------------
malloc(16384):
  total:   157.954 ms - average: 15.795 ns

ALLOC(16384):
  total:   200.505 ms - average: 20.050 ns

-----------------------------
malloc(80200):
  total:   156.740 ms - average: 15.674 ns

ALLOC(80200):
  total:   198.121 ms - average: 19.812 ns

-----------------------------
malloc(580200):
  total:   154.833 ms - average: 15.483 ns

ALLOC(580200):
  total:   203.087 ms - average: 20.309 ns

-----------------------------
malloc(1000000):
  total:   151.832 ms - average: 15.183 ns

ALLOC(1000000):
  total:   197.220 ms - average: 19.722 ns

-----------------------------
```

----

Compiled with (BASH): `gcc test.c -O0 && ./a.out`

```c
malloc(16):
  total:   64.897 ms - average: 6.490 ns

ALLOC(16):
  total:   108.467 ms - average: 10.847 ns

-----------------------------
malloc(64):
  total:   65.363 ms - average: 6.536 ns

ALLOC(64):
  total:   109.121 ms - average: 10.912 ns

-----------------------------
malloc(256):
  total:   64.754 ms - average: 6.475 ns

ALLOC(256):
  total:   113.369 ms - average: 11.337 ns

-----------------------------
malloc(1024):
  total:   67.590 ms - average: 6.759 ns

ALLOC(1024):
  total:   201.088 ms - average: 20.109 ns

-----------------------------
malloc(4096):
  total:   147.975 ms - average: 14.797 ns

ALLOC(4096):
  total:   200.226 ms - average: 20.023 ns

-----------------------------
malloc(16384):
  total:   157.148 ms - average: 15.715 ns

ALLOC(16384):
  total:   201.718 ms - average: 20.172 ns

-----------------------------
malloc(80200):
  total:   152.916 ms - average: 15.292 ns

ALLOC(80200):
  total:   198.833 ms - average: 19.883 ns

-----------------------------
malloc(580200):
  total:   151.531 ms - average: 15.153 ns

ALLOC(580200):
  total:   201.950 ms - average: 20.195 ns

-----------------------------
malloc(1000000):
  total:   154.376 ms - average: 15.438 ns

ALLOC(1000000):
  total:   205.782 ms - average: 20.578 ns

----------------------------
```

----

Compiled with (BASH): `gcc test.c -O1 && ./a.out`

```c
malloc(16):
  total:   58.203 ms - average: 5.820 ns

ALLOC(16):
  total:   96.049 ms - average: 9.605 ns

-----------------------------
malloc(64):
  total:   59.003 ms - average: 5.900 ns

ALLOC(64):
  total:   97.017 ms - average: 9.702 ns

-----------------------------
malloc(256):
  total:   58.268 ms - average: 5.827 ns

ALLOC(256):
  total:   96.865 ms - average: 9.687 ns

-----------------------------
malloc(1024):
  total:   61.851 ms - average: 6.185 ns

ALLOC(1024):
  total:   189.258 ms - average: 18.926 ns

-----------------------------
malloc(4096):
  total:   150.330 ms - average: 15.033 ns

ALLOC(4096):
  total:   185.259 ms - average: 18.526 ns

-----------------------------
malloc(16384):
  total:   153.612 ms - average: 15.361 ns

ALLOC(16384):
  total:   188.803 ms - average: 18.880 ns

-----------------------------
malloc(80200):
  total:   155.702 ms - average: 15.570 ns

ALLOC(80200):
  total:   189.328 ms - average: 18.933 ns

-----------------------------
malloc(580200):
  total:   155.897 ms - average: 15.590 ns

ALLOC(580200):
  total:   189.597 ms - average: 18.960 ns

-----------------------------
malloc(1000000):
  total:   151.871 ms - average: 15.187 ns

ALLOC(1000000):
  total:   190.655 ms - average: 19.066 ns

-----------------------------
```

----

Compiled with (BASH): `gcc test.c -O2 && ./a.out`

```c
malloc(16):
  total:   62.224 ms - average: 6.222 ns

ALLOC(16):
  total:   89.557 ms - average: 8.956 ns

-----------------------------
malloc(64):
  total:   61.608 ms - average: 6.161 ns

ALLOC(64):
  total:   88.623 ms - average: 8.862 ns

-----------------------------
malloc(256):
  total:   62.595 ms - average: 6.259 ns

ALLOC(256):
  total:   87.030 ms - average: 8.703 ns

-----------------------------
malloc(1024):
  total:   60.092 ms - average: 6.009 ns

ALLOC(1024):
  total:   177.378 ms - average: 17.738 ns

-----------------------------
malloc(4096):
  total:   158.412 ms - average: 15.841 ns

ALLOC(4096):
  total:   177.447 ms - average: 17.745 ns

-----------------------------
malloc(16384):
  total:   154.969 ms - average: 15.497 ns

ALLOC(16384):
  total:   187.303 ms - average: 18.730 ns

-----------------------------
malloc(80200):
  total:   155.696 ms - average: 15.570 ns

ALLOC(80200):
  total:   186.525 ms - average: 18.652 ns

-----------------------------
malloc(580200):
  total:   158.518 ms - average: 15.852 ns

ALLOC(580200):
  total:   184.136 ms - average: 18.414 ns

-----------------------------
malloc(1000000):
  total:   159.837 ms - average: 15.984 ns

ALLOC(1000000):
  total:   185.888 ms - average: 18.589 ns

-----------------------------
```

----

Compiled with (BASH): `gcc test.c -O3 && ./a.out`

```c
malloc(16):
  total:   58.627 ms - average: 5.863 ns

ALLOC(16):
  total:   81.525 ms - average: 8.153 ns

-----------------------------
malloc(64):
  total:   60.259 ms - average: 6.026 ns

ALLOC(64):
  total:   82.301 ms - average: 8.230 ns

-----------------------------
malloc(256):
  total:   57.891 ms - average: 5.789 ns

ALLOC(256):
  total:   82.127 ms - average: 8.213 ns

-----------------------------
malloc(1024):
  total:   59.021 ms - average: 5.902 ns

ALLOC(1024):
  total:   174.280 ms - average: 17.428 ns

-----------------------------
malloc(4096):
  total:   149.036 ms - average: 14.904 ns

ALLOC(4096):
  total:   173.838 ms - average: 17.384 ns

-----------------------------
malloc(16384):
  total:   153.703 ms - average: 15.370 ns

ALLOC(16384):
  total:   177.135 ms - average: 17.714 ns

-----------------------------
malloc(80200):
  total:   152.950 ms - average: 15.295 ns

ALLOC(80200):
  total:   180.891 ms - average: 18.089 ns

-----------------------------
malloc(580200):
  total:   152.631 ms - average: 15.263 ns

ALLOC(580200):
  total:   174.565 ms - average: 17.456 ns

-----------------------------
malloc(1000000):
  total:   153.607 ms - average: 15.361 ns

ALLOC(1000000):
  total:   177.416 ms - average: 17.742 ns

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
   * Slow compared to `malloc`

----

