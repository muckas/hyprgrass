test_exe = executable('test-gestures',
  'MockGestureManager.cpp',
  'test.cpp',
  link_with: gestures,
  dependencies: [
    wftouch,
    dependency('doctest')
  ]
)

test('test gestures', test_exe)
