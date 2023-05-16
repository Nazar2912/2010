print(f"NAmeError - {Type(NameError)}-{issubclass(NameError,BaseException)}")
print(f"ImportError - {type(ImportError)}-{issubclass(ImportError,BaseException)}")
print("ni")
try:
    print("stsrt")
    print(10/0)
    print("no error")
except NameError:
    print("We have am error")
    print("code after cpasulc")
