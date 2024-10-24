# aicommit

## 输入获取
```
git diff --staged
```

## 输入示例(上面运行的结果）
```
diff --git a/app/tools/page.tsx b/app/tools/page.tsx
index 55bb0d0..afd70c6 100644
--- a/app/tools/page.tsx
+++ b/app/tools/page.tsx
@@ -42,6 +42,7 @@ const input = `Tools
 - 💬 [The Comment](https://comment.uhaka.com/)
 - 📂 [The List of Directories for Startups and Indie Hackers](https://www.uhaka.com/listing)
 - 🖼️ [background remove](https://bgremoveabc.vercel.app/)
+- 📊 [fake Data](https://xxxx.uhaka.com/)
 - 💵 [The Pricing](https://www.uhaka.com/pricing)

 ## My Open Sources
@@ -64,6 +65,7 @@ const input = `Tools
  - 📊 [ai-benchmark-data](https://github.com/zgimszhd61/benchmark4GPT)
  - 📊 [the simplest self-building coding agent](https://github.com/zgimszhd61/orca)

+
 ## My Descriptions（ 🌐 [Contact me](https://x.com/seclink) ）

 Basic ability /w Keyword (welcome to contact me for cooperate and tell me what you want):
diff --git a/pyscript/dothing.py b/pyscript/dothing.py
index 4b6aa69..baa9894 100644
--- a/pyscript/dothing.py
+++ b/pyscript/dothing.py
@@ -35,7 +35,6 @@ def transform_to_json_format(text):

 # Example usage:
 input_text = """
-
 """
```

## 拼接到Prompt
```
分析提供的 git diff --staged 输出，识别关键的代码变更，包括新增或删除的功能，并提供一个不超过30字的简洁总结，说明此次提交的主要用途，重点关注其对代码或项目的影响。其中输入如下。
-------
{}
```
