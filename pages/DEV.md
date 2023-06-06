- # Tools
- Alacritty
- Tmux
- [[Nvim]]
- [Transcrypt](https://github.com/elasticdog/transcrypt)
	- #FishShell
		- encryptText.fish
		- ```
		  function encryptText
		      echo $argv | openssl aes-256-cbc -a -salt
		  end
		  ```
		- decryptText.fish
		- ```
		  function decryptText
		      echo $argv | openssl aes-256-cbc -a -d -salt
		  end
		  ```
		- encryptGitFile.fish
		- ```
		  function encryptGitFile
		    echo "$argv filter=crypt diff=crypt merge=crypt" >> .gitattributes;
		    git add .gitattributes $argv
		  end
		  ```
- # Articles
- #BTCMaximalist
	- [Cryptography is not enough](https://dergigi.com/2022/09/10/cryptography-is-not-enough/)
- #Web3
	- [Erc721 vs Erc721a Batch minting nfts](https://www.alchemy.com//blog/erc721-vs-erc721a-batch-minting-nfts)
	- [NFT drop with revenue share](https://blog.thirdweb.com/guides/nft-drop-with-revenue-share/)
	- #Storage
		- [[Arweave]]
- #Code
	- [From Junior to Genius: an optimization story](https://itnext.io/from-junior-to-genius-an-optimization-story-ab20afc8159d)
	- #Playground [Scroll Indicator](https://play.tailwindcss.com/cB8FNN70zd)
- #Curiosities
	- [Fourier Interactive Drawing](https://www.jezzamon.com/fourier/index.html)
- #Books
	- ## DSA
	- Grokking Algorithms - Aditya Bhargava
	- Introduction to Algorithms - Udi Manber
	- The Algorithm Design Manual - Steven S. Skiena
	- Algorithms - Robert Sedgewick, Kevin Wayne
	- Data Structures and Algorithms Made Easy - Narasimha Karumanchi
	- ## SQL/Database Design
	- SQL Practice Problems - Sylvia Moestl Vasilik
	- SQL Queries for Mere Mortals -  Michael J. Hernandez
	- SQL Antipatterns - Bill Karwin
	- ## Various
	- A Philosophy of Software Design, by John Ousterhout
	- Accelerate: The Science of Lean Software and DevOps, by Nicole Forsgren, Jez Humble, and Gene Kim
	- Build Your Own Programming Language
	- The Art of Statistics: How to Learn from Data, by David Spiegelhalter
	- Dive Into Design Patterns, by Alexander Shvets
	- System Design Interview – An insider’s guide, by Alex Xu
	- Practical Recommender Systems, by Kim Falk
	- Introduction to Algorithms, by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest
	- The Pragmatic Programmer: From Journeyman to Master, by Andy Hunt and Dave Thomas
	- Clean Code: A Handbook of Agile Software Craftsmanship by Robert C. Martin
	- Structure and Interpretation of Computer Programs, by Harold Abelson, Gerald Jay Sussman, and Julie Sussman
	- Code: The Hidden Language of Computer Hardware and Software, by Charles Petzold
	- Refactoring: Improving the Design of Existing Code, by Martin Fowler, Kent Beck, and Don Roberts
	- Designing Data-Intensive Applications, by Martin Kleppmann