project('wxTestPad', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3']
)

wx_dep = dependency(
  'wxwidgets', version : '>=3.0.0',
)

sources = files('wxtestpad.cpp', 'gui/buildergen/wxTpGUI.cpp', 'gui/wxTpGUIMainFrame.cpp')

executable('wxTestPad', sources,
  dependencies : [wx_dep],
  install : false
)
