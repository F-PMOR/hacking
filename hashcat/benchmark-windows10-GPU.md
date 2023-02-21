pmorry@Alienware:/usr/share/dict$ hashcat -b
hashcat (v6.2.5) starting in benchmark mode

Benchmarking uses hand-optimized kernel code by default.
You can use it in your cracking session by setting the -O option.
Note: Using optimized kernel code limits the maximum supported password length.
To disable the optimized kernel code in benchmark mode, use the -w option.

OpenCL API (OpenCL 2.0 pocl 1.8  Linux, None+Asserts, RELOC, LLVM 11.1.0, SLEEF, DISTRO, POCL_DEBUG) - Platform #1 [The pocl project]
=====================================================================================================================================
* Device #1: pthread-Intel(R) Core(TM) i7-4790 CPU @ 3.60GHz, 7094/14252 MB (2048 MB allocatable), 8MCU

Benchmark relevant options:
===========================
* --optimized-kernel-enable

-------------------
* Hash-Mode 0 (MD5)
-------------------

Speed.#1.........:   565.6 MH/s (13.82ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

----------------------
* Hash-Mode 100 (SHA1)
----------------------

Speed.#1.........:   239.9 MH/s (32.32ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

---------------------------
* Hash-Mode 1400 (SHA2-256)
---------------------------

Speed.#1.........: 93974.0 kH/s (88.78ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

---------------------------
* Hash-Mode 1700 (SHA2-512)
---------------------------

Speed.#1.........: 31442.5 kH/s (66.43ms) @ Accel:512 Loops:512 Thr:1 Vec:4

-------------------------------------------------------------
* Hash-Mode 22000 (WPA-PBKDF2-PMKID+EAPOL) [Iterations: 4095]
-------------------------------------------------------------

Speed.#1.........:    11007 H/s (79.15ms) @ Accel:1024 Loops:512 Thr:1 Vec:8

-----------------------
* Hash-Mode 1000 (NTLM)
-----------------------

Speed.#1.........:   914.5 MH/s (8.95ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

---------------------
* Hash-Mode 3000 (LM)
---------------------

Speed.#1.........:   105.0 MH/s (76.85ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

--------------------------------------------
* Hash-Mode 5500 (NetNTLMv1 / NetNTLMv1+ESS)
--------------------------------------------

Speed.#1.........:   651.5 MH/s (12.65ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

----------------------------
* Hash-Mode 5600 (NetNTLMv2)
----------------------------

Speed.#1.........: 41916.2 kH/s (99.73ms) @ Accel:512 Loops:1024 Thr:1 Vec:8

--------------------------------------------------------
* Hash-Mode 1500 (descrypt, DES (Unix), Traditional DES)
--------------------------------------------------------

Speed.#1.........:  4093.8 kH/s (56.38ms) @ Accel:32 Loops:1024 Thr:1 Vec:8

------------------------------------------------------------------------------
* Hash-Mode 500 (md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5)) [Iterations: 1000]
------------------------------------------------------------------------------

Speed.#1.........:    50569 H/s (78.68ms) @ Accel:1024 Loops:500 Thr:1 Vec:8

----------------------------------------------------------------
* Hash-Mode 3200 (bcrypt $2*$, Blowfish (Unix)) [Iterations: 32]
----------------------------------------------------------------

Speed.#1.........:       23 H/s (2.19ms) @ Accel:8 Loops:32 Thr:1 Vec:1

--------------------------------------------------------------------
* Hash-Mode 1800 (sha512crypt $6$, SHA512 (Unix)) [Iterations: 5000]
--------------------------------------------------------------------

Speed.#1.........:     2094 H/s (48.35ms) @ Accel:1024 Loops:512 Thr:1 Vec:4

--------------------------------------------------------
* Hash-Mode 7500 (Kerberos 5, etype 23, AS-REQ Pre-Auth)
--------------------------------------------------------

Speed.#1.........:  4115.8 kH/s (63.44ms) @ Accel:32 Loops:1024 Thr:1 Vec:8

-------------------------------------------------
* Hash-Mode 13100 (Kerberos 5, etype 23, TGS-REP)
-------------------------------------------------

Speed.#1.........:  4240.3 kH/s (61.60ms) @ Accel:128 Loops:256 Thr:1 Vec:8

---------------------------------------------------------------
* Hash-Mode 15300 (DPAPI masterkey file v1) [Iterations: 23999]
---------------------------------------------------------------

Speed.#1.........:     1604 H/s (105.66ms) @ Accel:512 Loops:1024 Thr:1 Vec:8

---------------------------------------------------------------
* Hash-Mode 15900 (DPAPI masterkey file v2) [Iterations: 12899]
---------------------------------------------------------------

Speed.#1.........:     1224 H/s (63.77ms) @ Accel:128 Loops:1024 Thr:1 Vec:4

------------------------------------------------------------------
* Hash-Mode 7100 (macOS v10.8+ (PBKDF2-SHA512)) [Iterations: 1023]
------------------------------------------------------------------

Speed.#1.........:    13811 H/s (70.19ms) @ Accel:128 Loops:1023 Thr:1 Vec:4

---------------------------------------------
* Hash-Mode 11600 (7-Zip) [Iterations: 16384]
---------------------------------------------

Speed.#1.........:     2509 H/s (49.82ms) @ Accel:64 Loops:4096 Thr:1 Vec:8

------------------------------------------------
* Hash-Mode 12500 (RAR3-hp) [Iterations: 262144]
------------------------------------------------

Speed.#1.........:      377 H/s (84.62ms) @ Accel:64 Loops:16384 Thr:1 Vec:8

--------------------------------------------
* Hash-Mode 13000 (RAR5) [Iterations: 32799]
--------------------------------------------

Speed.#1.........:     1235 H/s (103.32ms) @ Accel:1024 Loops:512 Thr:1 Vec:8

-----------------------------------------------------------------------
* Hash-Mode 6211 (TrueCrypt RIPEMD160 + XTS 512 bit) [Iterations: 1999]
-----------------------------------------------------------------------

Speed.#1.........:     9330 H/s (52.44ms) @ Accel:128 Loops:1024 Thr:1 Vec:8

-----------------------------------------------------------------------------------
* Hash-Mode 13400 (KeePass 1 (AES/Twofish) and KeePass 2 (AES)) [Iterations: 24569]
-----------------------------------------------------------------------------------

Speed.#1.........:      859 H/s (49.48ms) @ Accel:256 Loops:512 Thr:1 Vec:8

----------------------------------------------------------------
* Hash-Mode 6800 (LastPass + LastPass sniffed) [Iterations: 499]
----------------------------------------------------------------

Speed.#1.........:    76428 H/s (98.87ms) @ Accel:1024 Loops:499 Thr:1 Vec:8

--------------------------------------------------------------------
* Hash-Mode 11300 (Bitcoin/Litecoin wallet.dat) [Iterations: 200459]
--------------------------------------------------------------------

Speed.#1.........:      152 H/s (34.33ms) @ Accel:1024 Loops:1024 Thr:1 Vec:4

Started: Tue Feb 21 20:30:33 2023
Stopped: Tue Feb 21 20:41:57 2023
