[![bg][banner]][website]

### ~ Welcome aboard!

 <img src="https://readme-typing-svg.herokuapp.com?font=monospace&color=002AFF&size=25&center=true&vCenter=true&lines=⛓️+Full+Stack+Blockchain+Developer;Web3+Security+Researcher;" alt="Currently security researcher">



👨🏼‍💻 Building   
🧠 Learning <br/>
💜 Loving Stacks [React][react] , [Nodejs][nodejs] , [Typescript][typescript] , [Solidity ][Solidity] , [Ethers][ethers] , [Solana][solana] and [Tailwind][tailwind]  

🏡 [website][website] **|** 
🐦 [twitter][twitter] **|** 
📺 [youtube][youtube] **|** 
👔 [linkedin][linkedin]

<div style="text-align: left , color:red ">
</div>
   <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0429.gif" width="400px"> 
   
   ### <a href="https://www.animatedimages.org/cat-computer-56.htm"><img src="https://www.animatedimages.org/data/media/56/animated-computer-image-0026.gif" border="0" alt="animated-computer-image-0026" width="50px" height="50px"/></a> A little more about me...
   
 </div>
    

[banner]: https://github.com/KashifCh-eth/KashifCh-eth/blob/4cbded1f5a078f9e92b9749f43a7fe7a6fadf594/KashifCh.gif
[Solidity]: https://soliditylang.org/
[nodejs]: https://nodejs.org/en
[solana]:https://solana.com/
[typescript]: https://www.typescriptlang.org
[react]: http://reactjs.org
[ethers]: https://docs.ethers.org/v5/
[tailwind]: https://tailwindcss.com
[website]:  #
[twitter]: https://twitter.com/k_ashi0
[youtube]: https://www.youtube.com/channel/UCTV-ublGmEHqhX3n3RLiRJw
[linkedin]: https://www.linkedin.com/in/kashif-choudary/

``` solidity
    // SPDX-License-Identifier: MIT
    pragma solidity ^0.8.24;
    
    contract Profile {
        string public name = "KashifCh-eth";
        string public pronouns = "He | Him";
        string public currentFocus = "Web3 / dApps";
    
        string[] internal skills;
    
        function getSkills() public returns (string[] memory) {
            skills = [
                string("Javascript", "Rust"),
                "Next.js"
                "react",
                "Solidity",
                "Hardhat",
                "ethers"
                "Node.js"
                "Solana"
            ];
    
            return skills;
        }
    
          function fun() public view returns (string memory) {
        uint256 randomNumber = uint256(keccak256(abi.encodePacked(blockhash(block.number - 1), msg.sender)));

         if (randomNumber % 2 == 0) {
             return "Why do developers always carry a dictionary? Because they need to decode the error messages!";
        } else {
             return "Why did the blockchain break up with the database? It couldn't handle the blocks in the relationship!";
       }
     }

    }
 ```
    
   <br>
    
 
