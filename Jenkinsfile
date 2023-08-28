

println("HERE")
node {
  lock(resource: 'secure-browser') {
    sh script: "echo start sleeping"
    sh script: "sleep 30"
    sh script: "env"
    sh script: "echo woke up"
  }
}
