if not get_option('benchmarks').disabled()
  subdir('benchmarks')
endif
if not get_option('tests').disabled() and gst_check_dep.found()
  subdir('check')
endif
if not get_option('examples').disabled()
  subdir('examples')
endif
if not get_option('tools').disabled()
  subdir('misc')
endif
