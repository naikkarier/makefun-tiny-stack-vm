# makefun-tiny-stack-vm

A tiny stack virtual machine for make.fun's "Build a tiny stack virtual machine" bounty, $100 in USDC. `main.ts` implements the ISA faithfully, with every trap code, wrapping 32-bit arithmetic, unsigned division and shifts, and the step and output limits. Scored 1000/1000 on all 40 practice instances with `grade-local`.

Run: `MAKEFUN_INPUT_DIR=practice/input MAKEFUN_OUTPUT_DIR=out node main.ts`
