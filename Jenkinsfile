@Library('jenkins-workflow-libs@v2-generic') _

def buildParameterMap = [:]
buildParameterMap['appName'] = 'k8s-ecr-login-renew'
buildParameterMap['buildStrategy'] = [
 '*': [ 'checkout' , 'build', 'containerize'
  ]
]

buildAndDeployGeneric(buildParameterMap)

// vim: set ft=groovy:
