# cool-gan-sites and other stuff
Just makin a list of cool GAN related (and not GAN related) news sites/articles I find

## List
https://arxiv.org/abs/1406.2661

This is the paper by Ian Goodfellow that started it all.

https://blogs.nvidia.com/blog/2020/05/22/gamegan-research-pacman-anniversary/

This article claims to have "Trained on 50,000 episodes of the game [Pacman], a powerful new AI model created by NVIDIA Research, called NVIDIA GameGAN." There is no underlying game engine; just a trained neural network trained on Pacman.

https://thisxdoesnotexist.com/

This site has a nice UI and a list of sites in the format "thisxdoesnotexist.com," where the x is some item generated by a GAN. The things you would see do not actually exist in real life.

https://arxiv.org/pdf/2006.03511.pdf
Unsupervised Translation of Programming Languages
This is a paper by Facebook AI Research that delves into determining if it's possible to "translate" one programming language to another in the same way that you 
translate one traditional language to another.
Here is the abstract: 
>>A transcompiler, also known as source-to-source translator, is a system that convertssource code from a high-level programming language (such as C++ or Python)to another.  Transcompilers are primarily used for interoperability, and to portcodebases written in an obsolete or deprecated language (e.g. COBOL, Python 2)to a modern one. They typically rely on handcrafted rewrite rules, applied to thesource code abstract syntax tree.  Unfortunately, the resulting translations oftenlack readability, fail to respect the target language conventions, and require manualmodifications in order to work properly. The overall translation process is time-consuming and requires expertise in both the source and target languages, makingcode-translation projects expensive. Although neural models significantly outper-form their rule-based counterparts in the context of natural language translation,their applications to transcompilation have been limited due to the scarcity of paral-lel data in this domain. In this paper, we propose to leverage recent approaches inunsupervised machine translation to train a fully unsupervised neural transcompiler.We train our model on source code from open source GitHub projects, and showthat it can translate functions between C++, Java, and Python with high accuracy.Our method relies exclusively on monolingual source code, requires no expertise inthe source or target languages, and can easily be generalized to other programminglanguages. We also build and release a test set composed of 852 parallel functions,along with unit tests to check the correctness of translations.  We show that ourmodel outperforms rule-based commercial baselines by a significant margin.
