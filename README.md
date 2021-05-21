# Fission newdeploy issues
- Each spec uses the same identifer names so have to `fission spec destroy` before running `fission spec apply`
- These were tested running fission 1.12 on EKS 1.18
    ```
    client:
      fission/core:
        BuildDate: "2021-02-11T13:35:47Z"
        GitCommit: ca1a0d4d67a78dd4eaa7790408549d8fb6fc20ca
        Version: 1.12.0
    server:
      fission/core:
        BuildDate: "2021-02-11T13:35:47Z"
        GitCommit: ca1a0d4d67a78dd4eaa7790408549d8fb6fc20ca
        Version: 1.12.0
    
    ```
