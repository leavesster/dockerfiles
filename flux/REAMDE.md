# flux

目前问题，docker exec 到容器内，按照官方文档执行 build 可以成功构建，但是在 docker run 中无法构建，报错：

```bash
 => => # Determined module root{"path": "/home/flux"}                                                                                                                                                          
 => => # Flux module is the main module{"modroot": "/home/flux"}                                                                                                                                               
 => => # Could not determine version from base path{"error": "directory path did not match the module pattern: /home/flux"}                                                                                    
 => => # Executing cargo build{"dir": "/home/flux/libflux", "target": "aarch64-unknown-linux-gnu"}                                                                                                             
 => => # Error installing library{"name": "flux", "error": "exec: \"cargo\": executable file not found in $PATH"}                                                                                              
 => => # pkg-config: exit status 1  
```