# PROGRAM18
.def strip_chars(s, chars):
    return "".join(c for c in s if c not in chars)
print("\nOriginal String: ")
print("The quick brown fox jumps over the lazy dog.")
print("After stripping a, e, i, o, u:")
print(strip_chars("The quick brown fox jumps over the lazy dog.", "aeiouAEIOU"))
print()

output:Original String: 
The quick brown fox jumps over the lazy dog.
After stripping a, e, i, o, u:
Th qck brwn fx jmps vr th lzy dg.
