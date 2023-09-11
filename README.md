# zk-resources
Random collection of resources I found most helpful in learning ZK and writing circuits from an app / Solidity developer's perspective. Will keep updating this list over time as I learn more

Reach out to me at:
- [Twitter](https://twitter.com/richardzliang)

## Courses
- [ZKIAP](https://zkiap.com/)
- [Berkeley MOOC](https://zk-learning.org/)
- [0xParc Circom](https://learn.0xparc.org/materials/circom/learning-group-1/circom-1/)
- [0xParc Halo2](https://learn.0xparc.org/halo2/)
- [ZK Whiteboard Sessions](https://www.youtube.com/playlist?list=PLj80z0cJm8QErn3akRcqvxUsyXWC81OGq)

## Overall DSLs
- [ZKSummit10 DSL Workshop Slides - Halo2, Circom or Noir? - Richard Liang](https://docs.google.com/presentation/d/1cGnYiiVXtLtCwEgQ0w-dIQnVViZaC8AKMPFWLQ-I8x0/edit#slide=id.g1e6cbe9af1e_2_0)
- [ZKSummit10 DSL Workshop Exercises - Richard Liang](https://github.com/richardliang/zkdsl-workshop)
- [A beginner's intro to coding ZKPs - Santiago Palladino](https://dev.to/spalladino/a-beginners-intro-to-coding-zero-knowledge-proofs-c56)

## ZK Theory
- [Scroll ZK Proof Systems Workshop - Ye Zhang](https://drive.google.com/file/d/12-e1g8Ad7q0avIOge-NELNBaDlpmk0TV/view): Clearest explanation of how a ZKP is constructed in the proving stack (from computation to argument). Tldwatch: jump to 30:00
![image](https://github.com/richardliang/zk-resources/assets/6797244/d2e6da02-f016-4e14-84d9-f000947edd21)
- [From AIRs to RAPs - how PLONK-style arithmetization works - Aztec](https://hackmd.io/@aztec-network/plonk-arithmetiization-air) Good overview on 
- [0xSachinK's Berkeley MOOC Notes](https://github.com/0xSachinK/zkp-mooc-notes)
- [Number Theoretic Transforms](https://www.youtube.com/watch?v=Pct3rS4Y0IA&list=PLcPzhUaCxlCjdhONxEYZ1dgKjZh3ZvPtl&index=5)\

## Circom
- [ZKRepl](https://zkrepl.dev/) Easy prototyping circom circuits

## Halo2
- [Little Things I’ve Learned in Developing Halo2 Circuits by Chih-Cheng Liang](https://www.youtube.com/watch?v=wSfkpJDq8AI): Good walkthrough of a vanilla Halo2 example and tricks to think like a circuit dev (e.g. what to do when there's no if statements)
- [Halo2 Cheatsheet](https://hackmd.io/@axiom/HyoXzD7Zh) Some handy tips and tricks when writing halo2 circuits. e.g Chips vs configs vs circuits
- [Axiom docs](https://docs.axiom.xyz/zero-knowledge-proofs/getting-started-with-halo2) I just use Axiom's halo2-lib, and don't write vanilla halo2 at all. Good place to get started

## Noir
- [Intro to Noir](https://www.youtube.com/watch?v=5CziMfChveY) First video I watched on Noir
- [Noir Halo2 Backend - Mach34](https://mach-34.github.io/halo2_backend_docs/getting_started/) Docs that explain the Noir ACIR process
- [Noir RSA](https://github.com/SetProtocol/noir-rsa) Library to verify RSA signatures in Noir
