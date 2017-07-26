# MScTI_APC
Accompanying material for course "Advanced Parallel Computing", Institute of Computer Engineering, Ruprecht-Karls University of Heidelberg, Germany

Part of MSc Computer Engineering

# Overview 

This course deepens the knowledge in the area of parallel computing. Focus is set on shared-memory architectures, as current trends indicate an increasing use of such architectures. Initially, aspects of synchronization are explained and how they impact cache-coherent shared-memory architectures (locks, barriers). The following lectures pay attention to the snooping coherence, scalable coherence, foundations of consistency models and relaxed consistency models. Frequently, important research directions are reviewed and put into context with regard to commercially available solutions. In the context of research, of particular interest is transactional memory, token-based coherence, and non-uniform cache architectures. The course ends with a review of current CMOS trends and constraints, their implications, and a short review of deep learning as an emerging workload.

# Outline 

| Lecture | Slides | Exercise material |
| --- | --- | --- |
| Lecture 01: Introduction | [slides (pdf)](lectures/lec01.pdf) | [exercise (pdf)](exercises/exercise01.pdf) |
| Lecture 02: Shared Memory Architectures | [slides (pdf)](lectures/lec02.pdf) | [exercise (pdf)](exercises/exercise02.pdf), [code (C)](exercises/exercise02_mem_hierarchy.c) |
| Lecture 03: Snooping Coherence | [slides (pdf)](lectures/lec03.pdf) | [exercise (pdf)](exercises/exercise03.pdf) |
| Lecture 04: Synchronization I | [slides (pdf)](lectures/lec04.pdf) | [exercise (pdf)](exercises/exercise04.pdf) |
| Lecture 05: Synchronization II | [slides (pdf)](lectures/lec05.pdf) | [exercise (pdf)](exercises/exercise05.pdf) |
| Lecture 06: Transactional Memory | [slides (pdf)](lectures/lec06.pdf) | [exercise (pdf)](exercises/exercise06.pdf) |
| Lecture 07: Scalable Coherence | [slides (pdf)](lectures/lec07.pdf) | |
| Lecture 08: Token Coherence | [slides (pdf)](lectures/lec08.pdf) | |
| Lecture 09: Memory Consistency | [slides (pdf)](lectures/lec09.pdf) | |
| Lecture 10: Advanced Topics: SVM, MTA, NUCA | [slides (pdf)](lectures/lec10.pdf) | |
| Lecture 11: Constraints, Trends and Deep Learning | [slides (pdf)](lectures/lec11.pdf) | |


# License
Copyright (c) 2017, Computer Engineering Group at Ruprecht-Karls University of Heidelberg, Germany. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
* Neither the name of Ruprecht-Karls University of Heidelberg nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL COPYRIGHT HOLDER BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
