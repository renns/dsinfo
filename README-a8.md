# Publish Steps

## Scala JVM
`sbt ";project dsinfo;+ clean;+ publish"`

## Scala JS 0.6
`sbt -DscalaJSVersion=0.6.33 ";project dsinfo;+ clean;+ publish"`

## Scala JS 1
`sbt -DscalaJSVersion=1.1.1 ";project dsinfo;+ clean;+ publish"`
