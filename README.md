# OS Security Case Study

This repository contains a short case study on **iOS security**, how early jailbreaks exposed weaknesses, and how Apple strengthened the OS with layers like sandboxing, code signing, ASLR, DEP, KTRR, and PAC.

To understand these ideas practically, I **simulated core security mechanisms on Linux** to see how the kernel enforces privilege boundaries in real time.

---

## 🔍 What’s Included

### **1. System Call Validation**
A simple C program showing how the Linux kernel responds to valid vs. invalid system calls.

### **2. Seccomp Sandboxing**
A minimal example that restricts a program to one syscall and terminates it when anything else is attempted.

### **3. SUID Privilege Escalation Basics**
A demonstration of how permission misconfigurations can lead to elevated access — a foundational jailbreak concept.

---

## 📄 Case Study PDF
The full PDF is available in the repository.

---

## 👥 Authors
- **Anjali Patil**  
- **Anannya Samudra**

---

## 📌 Summary
This project connects **OS theory with practical kernel behavior**, offering a hands-on look at syscall filtering, sandboxing, and privilege boundaries.

