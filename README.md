# FPC_PATCH
maxOSX IME Patch for Lazarus 2.3.0 and FPC 3.2.2
FILE: FPC_OSX_LCL_PATCH.7z 
1. lcl_interface_cocoa.zip 解決LAZARUS IDE 無法輸入中文的問題，連日文romaji 輸入法也處理。
2. wincontrol.inc.zip and lcl.zip 加入新的EVENT 到TFORM 中，這不會影響到原有的程式。
3. prj1.zip is a demo 教你如何使用這三個新的EVENT。

FIX procedure
1. 蓋過和檔名對應的目錄的檔案，全都是OVERWRITE，無新檔。
2. 打開LAZARUS IDE，選TOOLS-->CONFIGURE "REBUILD LAZARUS" -->勾選CLEAN ALL -->按BUILD


註: 永遠以wincontrol.zip 的內容為準
