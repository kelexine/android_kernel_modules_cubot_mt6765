# UIFIRST scheduler core. Required by the scheduler (core.c, fair.c, cpupri.c,
# eas_plus.c) now that the OPLUS_FEATURE_UIFIRST flag has been removed and the
# ux task tracking WALT depends on is built unconditionally.
obj-y += uifirst_sched_common.o

# Locking/futex/workqueue ux boosts are not referenced by the scheduler and need
# ux_dep_task fields in struct mutex/rw_semaphore. They stay unbuilt, as they
# were before, until the locking side is brought over.
# obj-y += uifirst_sched_mutex.o
# obj-y += uifirst_sched_rwsem.o
# obj-y += uifirst_sched_futex.o
# obj-y += uifirst_sched_workqueue.o
