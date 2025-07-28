# MOD-kit

批处理 删除 `文件夹与子文件夹`里面 `扩展名为.res` 的所有文件
删除
```sh
@for /f "delims=" %f in ('dir /s /b /a-d *.res') do @del /f /q "%f"
```
