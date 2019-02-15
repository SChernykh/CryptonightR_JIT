Minimalistic JIT code generator for random math sequence in CryptonightR.

Usage:
- Allocate writable and executable memory
- Call v4_generate_JIT_code with "buf" pointed to memory allocated on the previous step
- Call the generated code instead of "v4_random_math(code, r)", omit the "code" parameter
