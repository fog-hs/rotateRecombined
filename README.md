building in the directory containing rotateRecombined.cabal with;      
cabal new-configure --allow-new   
cabal new-configure --allow-new   

gives the error   
...   
... build\x86_64-windows\ghc-8.6.3\rotatePlugin-0\l\rotate\rotatePlugin-0-inplace-rotate+J2GqyQnwOe9EPaywJQDMxw\build\rotatePlugin-0-inplace-rotate+J2GqyQnwOe9EPaywJQDMxw\autogen\: openBinaryTempFileWithDefaultPermissions: invalid argument (invalid argument)   
cabal: Failed to build lib:rotate from rotatePlugin-0 (which is required by exe:rotate-example from rotatePlugin-0).   
Failed to build lib:rotate from rotatePlugin-0 (which is required by exe:rotate-example from rotatePlugin-0).   
