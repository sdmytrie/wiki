:logging:stacktrace:

# Logging

## Logginf with stacktrace

<!---->

    import logging
    try:
      a = [1, 2, 3]
      val = a[4]
    except IndexError as e:
      logginf.error(e, exc_info=true)
