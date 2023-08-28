

println("HERE")
node {
  lock(resource: 'secure-browser', resourceSelectStrategy: '') {
    sh script: "echo start sleeping"
    sh script: "sleep 60"
    sh script: "echo woke up"
  }
}
