target(
  name = 'all',
  dependencies = [
    ':examples',
  ]
)

target(
  name = 'examples',
  dependencies = [
    ':test_pingpong_server',
  ]
)

python_tests(
  name = 'test_pingpong_server',
  sources = ['test_pingpong_server.py'],
  dependencies = [
    'src/python/twitter/common/testing',
    'src/python/twitter/common/examples:libpingpong',
  ]
)
