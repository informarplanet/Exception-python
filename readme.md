#outpout
Python provides effective methods that allow you to observe exceptions, identify 
them, and handle them efficiently. This is possible since all potential exceptions have 
their unambiguous names, so you can categorize them and react appropriately. We 
will review some tools in the Development environments for Python scripting section 
with some interesting techniques such as debugging.

+---BaseExceptionGroup
| +---ExceptionGroup
+---Exception
| +---ArithmeticError
| | +---FloatingPointError
| | +---OverflowError
| | +---ZeroDivisionError
| +---AssertionError
| +---AttributeError
| +---BufferError
| +---EOFError
| +---ImportError
| | +---ModuleNotFoundError
| | +---ZipImportError
| +---LookupError
| | +---IndexError
| | +---KeyError
| | +---CodecRegistryError
| +---MemoryError
| +---NameError
| | +---UnboundLocalError
| +---OSError
| | +---BlockingIOError
| | +---ChildProcessError
| | +---ConnectionError
| | | +---BrokenPipeError
| | | +---ConnectionAbortedError
| | | +---ConnectionRefusedError
| | | +---ConnectionResetError
| | +---FileExistsError
| | +---FileNotFoundError
| | +---InterruptedError
| | +---IsADirectoryError
| | +---NotADirectoryError
| | +---PermissionError
| | +---ProcessLookupError
| | +---TimeoutError
| | +---UnsupportedOperation
| +---ReferenceError
| +---RuntimeError
| | +---NotImplementedError
| | +---RecursionError
| | +---_DeadlockError
| +---StopAsyncIteration
| +---StopIteration
| +---SyntaxError
| | +---IndentationError
| | | +---TabError
| +---SystemError
| | +---CodecRegistryError
| +---TypeError
| +---ValueError
| | +---UnicodeError
| | | +---UnicodeDecodeError
| | | +---UnicodeEncodeError
| | | +---UnicodeTranslateError
| | +---UnsupportedOperation
| +---Warning
| | +---BytesWarning
| | +---DeprecationWarning
| | +---EncodingWarning
| | +---FutureWarning
| | +---ImportWarning
| | +---PendingDeprecationWarning
| | +---ResourceWarning
| | +---RuntimeWarning
| | +---SyntaxWarning
| | +---UnicodeWarning
| | +---UserWarning
| +---ExceptionGroup
+---GeneratorExit
+---KeyboardInterrupt
+---SystemExit