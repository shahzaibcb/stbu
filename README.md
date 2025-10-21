STBU monthly reporting


avg:trace.wordpress.request{env:mswpstbuotis-production}
formula: a/1000

sum:trace.wordpress.request.hits{env:mswpstbuotis-production}.as_count()
