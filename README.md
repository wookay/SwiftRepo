### SwiftPkgA

```
~/swift/SwiftPkgA$ swift package init --type library
Creating library package: SwiftPkgA
Creating Package.swift
Creating README.md
Creating .gitignore
Creating Sources/
Creating Sources/SwiftPkgA/SwiftPkgA.swift
Creating Tests/
Creating Tests/LinuxMain.swift
Creating Tests/SwiftPkgATests/
Creating Tests/SwiftPkgATests/SwiftPkgATests.swift
Creating Tests/SwiftPkgATests/XCTestManifests.swift
```



### SwiftTestX

```
~/swift/SwiftTestX$ swift package init --type executable
Creating executable package: SwiftTestX
Creating Package.swift
Creating README.md
Creating .gitignore
Creating Sources/
Creating Sources/SwiftTestX/main.swift
Creating Tests/
Creating Tests/LinuxMain.swift
Creating Tests/SwiftTestXTests/
Creating Tests/SwiftTestXTests/SwiftTestXTests.swift
Creating Tests/SwiftTestXTests/XCTestManifests.swift

~/swift/SwiftTestX$ swift run
[7/7] Linking SwiftTestX
Hello, world!


~/swift/SwiftTestX$ swift run
[2/2] Merging module SwiftPkgA
hello macOS
```



### SwiftAppX

```
~/swift/SwiftAppX/AppX
```
  - `file://`
