Unit Version: 2022.3.55f1

There seems to be two ways for running SLANG in unity:
1. SLANG plugin: https://github.com/pema99/SlangUnityPlugin which is composed via Harmony and C# (awaiting test)
2. compose the SLANG in official SLANG playground, compile as HLSL, then input into unity (awaiting test)

Logs
2/14/2026: imported SLANG plugin and testing SLANG shader template given, which looks more like HLSL and does not looks like SLANG
2/14/2026: confirmed that the SLANG plugin allows us to write slang codes in CGPROGRAM and CGINCLUDE blocks (insert anywhere), it's unknown which feature is supported
2/14/2026: initially confirmed that auto-differentiation is allowed in Unity SLANG plugin