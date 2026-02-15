# RISC-V Development Kit

A repository for getting started with RISC-V Assembly language.

I am excited about RISC-V and what it means for modern advances in computer software. Basically RISC-V is the fifth (that's why Roman numeral V) generation in RISC Central Processing Unit architecture.

RISC is an acronym for Reduced Instruction Set Computer. The idea is an instruction set for Assembly language that has less to learn than complicated sets like that of Intel x86 machines.

There are a few simulators I have used and had some success with. I will give you some pointers on the pros and cons of each.

Jupiter is my favorite because I really like the editor and interface, however I must admit that it executes a lot slower. There is some documentation that looks like pages are missing and it was never finished.

<https://jupitersim.gitbook.io/jupiter>

RARS runs a lot faster than Jupiter and the environment calls are mostly the same. However it uses different registers to call the functions so it is important to check the available documentation that you can access when you run the jar file as a GUI app without any arguments. The documentation is a lot more complete within this program compared to Jupiter.

Venus is an older simulator but from my experience, it seems to execute faster than even RARS. I don't know as much about it but will add more when I do.

But what I can tell you is that to declare strings, you need to use the .asciiz directive rather than .asciz as you would in RARS or Jupiter. Appendix A of Robert Winkler's book covers some of the differences between Venus and RARS. Venus supports fewer ecalls than RARS and Jupiter do, but is still good for getting started if you don't need user input.

# Learning RISC-V

The best book I can recommend is "RISC-V Assembly Programmming" by Robert Winkler. He really explains it well and was the first source I learned it from. He covers mostly the RARS simulator and some about Venus as well.

<https://www.robertwinkler.com/projects/riscv_book/riscv_book.html>