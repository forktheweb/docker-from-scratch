# 0.8.4

formatter/text: fix data race (#218)

# 0.8.3

logrus/core: fix entry log level (#208)
logrus/core: improve performance of text formatter by 40%
logrus/core: expose `LevelHooks` type
logrus/core: add support for DragonflyBSD and NetBSD
formatter/text: print structs more verbosely

# 0.8.2

logrus: fix more Fatal family functions

# 0.8.1

logrus: fix not exiting on `Fatalf` and `Fatalln`

# 0.8.0

logrus: defaults to stderr instead of stdout
hooks/sentry: add special field for `*http.Request`
formatter/text: ignore Windows for colors

# 0.7.3

formatter/\*: allow configuration of timestamp layout

# 0.7.2

formatter/text: Add configuration option for time format (#158)
