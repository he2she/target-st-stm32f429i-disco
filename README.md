yotta Target Description using GCC to compile for STM32F429I-DISCO

# 変更点
```
diff --git a/target.json b/target.json
index 1b34c53..282650d 100644
--- a/target.json
+++ b/target.json
@@ -2,7 +2,7 @@
   "name": "stm32f429i-disco-gcc",
   "version": "0.0.20",
   "inherits": {
-    "mbed-gcc": "*"
+    "mbed-gcc": "ARMmbed/target-mbed-gcc#v1.2.2"
   },
   "description": "Official mbed build target for the mbed stm32f429i-disco development board.",
   "licenses": [
```