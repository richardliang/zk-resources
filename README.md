# zk-resources
Random collection of resources I found most helpful in learning ZK and writing circuits from an app / Solidity developer's perspective. Will keep updating this list over time as I learn more

Reach out on [Twitter](https://twitter.com/richardzliang)

## Overall on DSLs
- [An Opinionated Overview of ZK Tooling and Proof Systems Right Now - Aayush](https://blog.aayushg.com/posts/zk/) Very clear overview on the current state of ZK tooling from an app / protocol builder's / 3rd party's perspective. Not from any ZK specific team shilling their own language
- [ZKSummit10 DSL Workshop Exercises - Richard Liang](https://github.com/richardliang/zkdsl-workshop) Exercises and solutions on implementing integer division in Noir, Circom and halo2
- [A beginner's intro to coding ZKPs - Santiago Palladino](https://dev.to/spalladino/a-beginners-intro-to-coding-zero-knowledge-proofs-c56)
- [Best practices for large Circom circuits](https://hackmd.io/V-7Aal05Tiy-ozmzTGBYPA?view#Compilation-and-proving) Setup for your machine for generating keys for large circom circuits

## ZK Theory
- [Scroll ZK Proof Systems Workshop - Ye Zhang](https://drive.google.com/file/d/12-e1g8Ad7q0avIOge-NELNBaDlpmk0TV/view): Clearest explanation of how a ZKP is constructed in the proving stack (from computation to argument). Tldwatch: jump to 30:00
![image](https://github.com/richardliang/zk-resources/assets/6797244/d2e6da02-f016-4e14-84d9-f000947edd21)
- [From AIRs to RAPs - how PLONK-style arithmetization works - Aztec](https://hackmd.io/@aztec-network/plonk-arithmetiization-air) 
- [0xSachinK's Berkeley MOOC Notes](https://github.com/0xSachinK/zkp-mooc-notes) Summarizes the Berkeley MOOC lectures so I don't have to rewatch the videos
- [Number Theoretic Transforms](https://www.youtube.com/watch?v=Pct3rS4Y0IA&list=PLcPzhUaCxlCjdhONxEYZ1dgKjZh3ZvPtl&index=5) Found this video really clear at explaining FFTs / NTTs
- [Benchmarks - Celer](https://blog.celer.network/2023/08/04/the-pantheon-of-zero-knowledge-proof-development-frameworks/) Good article on benchmarks for different proving systems. Choosing a proving stack still depends on your circuit though

## Circom
- [ZKRepl](https://zkrepl.dev/) Easy prototyping circom circuits
- [Solution to Axiom OS program (filter and pad)](https://twitter.com/axiomintern/status/1689751065422381058)
- [Solution to Succinct OS program (Var SHA256) - 0xSachinK](https://twitter.com/0xSachinK/status/1702744016432099669)

## Halo2
- [Little Things I’ve Learned in Developing Halo2 Circuits by Chih-Cheng Liang](https://www.youtube.com/watch?v=wSfkpJDq8AI): Good walkthrough of a vanilla Halo2 example and tricks to think like a circuit dev (e.g. what to do when there's no if statements)
- [Halo2 Cheatsheet](https://hackmd.io/@axiom/HyoXzD7Zh) Some handy tips and tricks when writing halo2 circuits. e.g Chips vs configs vs circuits
- [Axiom docs](https://docs.axiom.xyz/zero-knowledge-proofs/getting-started-with-halo2) I just use Axiom's halo2-lib, and don't write vanilla halo2 at all. Good place to get started

## Noir
- [Intro to Noir](https://www.youtube.com/watch?v=5CziMfChveY) First video I watched on Noir
- [Noir Halo2 Backend - Mach34](https://mach-34.github.io/halo2_backend_docs/getting_started/) Docs that explain the Noir ACIR process
- [Noir RSA](https://github.com/SetProtocol/noir-rsa) Library to verify RSA signatures in Noir

## Plonky2

## Courses
- [ZKIAP](https://zkiap.com/)
- [Berkeley MOOC](https://zk-learning.org/)
- [0xParc Circom](https://learn.0xparc.org/materials/circom/learning-group-1/circom-1/)
- [0xParc Halo2](https://learn.0xparc.org/halo2/)
- [ZK Whiteboard Sessions](https://www.youtube.com/playlist?list=PLj80z0cJm8QErn3akRcqvxUsyXWC81OGq)
