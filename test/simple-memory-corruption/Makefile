EXECUTABLES := \
    double_free_large \
    double_free_large_delayed \
    double_free_small \
    double_free_small_delayed \
    unaligned_free_large \
    unaligned_free_small \
    read_after_free_large \
    read_after_free_small \
    write_after_free_large \
    write_after_free_large_reuse \
    write_after_free_small \
    write_after_free_small_reuse \
    read_zero_size \
    write_zero_size \
    invalid_free_protected \
    invalid_free_unprotected \
    invalid_free_small_region \
    invalid_free_small_region_far \
    uninitialized_free \
    uninitialized_realloc \
    uninitialized_malloc_usable_size \
    eight_byte_overflow_small \
    eight_byte_overflow_large \
    string_overflow \
    delete_type_size_mismatch

all: $(EXECUTABLES)

clean:
	rm -f $(EXECUTABLES)
