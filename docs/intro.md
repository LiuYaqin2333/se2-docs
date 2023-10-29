---
sidebar_position: 1
slug: /
---

# 🏗 Welcome to Scaffold-ETH 2

[Scaffold-eth](https://github.com/scaffold-eth/scaffold-eth-2) is everything you need to get started building decentralized applications on Ethereum! 🚀

⚙️ Built using NextJS, RainbowKit, Hardhat, Foundry, Wagmi, and Typescript.

## About Scaffold-ETH 2

Scaffold-eth is an open-source, up-to-date toolkit for building decentralized applications (dapps) on the Ethereum blockchain. It's designed to make it easier for developers to create and deploy smart contracts and build user interfaces that interact with those contracts.

- ✅ **Contract Hot Reload**: Your frontend auto-adapts to your smart contract as you edit it.
- 🔥 **Burner Wallet & Local Faucet**: Quickly test your application with a burner wallet and local faucet.
- 🔐 **Integration with Wallet Providers**: Connect to different wallet providers and interact with the Ethereum network.

## Scaffold-ETH 2 Tech Stack

Scaffold-eth is not a product itself but more of a combination or stack of other great tools. It allows you to quickly build and iterate over your smart contracts and frontends.

Here are the main components:

- [**Hardhat**](https://hardhat.org/docs) or [**Foundry**](https://book.getfoundry.sh/) (user's choice) for running local networks, deploying and testing smart contracts.
- [**Wagmi**](https://wagmi.sh/react/getting-started) for React Hooks to start working with Ethereum.
- [**NextJS**](https://nextjs.org/docs) for building a frontend, using many useful pre-made hooks.
- [**RainbowKit**](https://www.rainbowkit.com/docs/) for adding wallet connection.
- [**DaisyUI**](https://daisyui.com/docs/) for pre-built [Tailwind CSS](https://tailwindui.com/components) components.



*Project background:*

 There are several complexities and ambiguities in governance in traditional DAOs:

First of all, traditional DAOs might face challenges related to power centralization, where a few individuals or entities hold significant decision-making power or a lack of clarity in how decentralized the decision-making process actually is.

Second, these DAOs may lack clear decision-making processes. This ambiguity can result in confusion or inconsistency in decision-making due to the absence of structured protocols.

What’s more,  as the DAO scales or deals with various stakeholders, the governance structure might become complex. It becomes challenging to manage and coordinate multiple inputs from diverse participants, leading to inefficiencies.

Also, in a single-level structure, the participation of members at different hierarchical levels might be restricted, limiting the expression of varied needs and interests within the organization.

Finally, the definition and allocation of roles and responsibilities might be unclear, leading to overlapping functions or a lack of accountability among the members.

These challenges contribute to governance complexities and ambiguities within traditional DAOs, potentially hindering effective decision-making, participation, and the overall efficiency of the organization. Solutions, such as implementing multi-layered hierarchical structures using subdomains, seek to address and mitigate these issues to create a more structured and efficient governance model.

*Technical architecture (need modify) :*

**Blockchain Infrastructure:** Leveraging a SOLIDITY to create and deploy smart contracts that manage the governance and functionalities of the DAO.

**Smart Contracts:** Designing and implementing multiple layers of smart contracts that control and manage different aspects of the DAO. These smart contracts could regulate member access, voting rights, and other governance functions.

**Frontend Development Tools:** Implementing React to create the user interface where members can participate in voting, view the hierarchical structure, and execute governance functions.

1. **Security Measures:** Given the involvement in decentralized finance (DeFi) and governance, security is crucial. This might include security audits, fixing contract vulnerabilities, and implementing best practices for security.
2. **Multi-Signature and Identity Verification:** Employing multi-signature mechanisms and identity verification procedures to ensure security and prevent malicious activities.

**Database and Backend Handling:** Managing the hierarchical levels, member information, and backend server-side processing for interacting with the front end application.

The technical architecture combines blockchain technology, smart contract development,  frontend and backend development, security measures, and identity verification to construct an organized, flexible, and secure hierarchical DAO system using subdomains.

*Function module:*

**Hierarchy Management:** Define and manage different hierarchical levels within the DAO, each represented by subdomains. Each level have its own set of rules, roles, and responsibilities.

**Voting Mechanisms:** Implement voting systems that cater to each hierarchical level, enabling members to vote based on their designated roles within the DAO.

**Role Assignment and Access Control:** Administer permissions and roles specific to each hierarchical layer. Grant access and permissions based on the member's position within the hierarchy.

**Governance Policies:** Establish governance rules and policies for decision-making at various levels, ensuring transparency and fairness in the decision process.

**Smart Contract Functionality:** Develop smart contracts that manage the interactions and operations within the hierarchical DAO, defining the rules and functionalities governing each layer.

**Data and Membership Management:** Manage member data, roles, and other information relevant to the DAO structure across different levels.

**Security Measures:** Implement security protocols to protect against unauthorized access, ensuring the integrity and security of the DAO’s operations.

*Interactive Process:*

**Hierarchy Establishment:** Define and establish the hierarchical structure within the DAO, with each level represented by specific subdomains.

**Member Participation:** Members interact through a user interface that allows them to access their specific hierarchical level, view governance proposals, and participate in decision-making processes.

**Proposal Submission:** Any member within a particular level can submit proposals for governance changes, improvements, or any other relevant issues.

**Voting Mechanism:** Proposals are presented to members at the respective level for voting. Each member's voting weight may be determined by their role or the level they belong to.

**Decision Implementation:** After a voting period, decisions are made based on the results. Implemented decisions could affect rules, policies, resource allocation, or other governance aspects within that level.

**Communication and Transparency:**Transparency is key. The process involves communication of results, making all decisions and their outcomes visible to all members within their respective levels, and ensuring accountability and transparency.

**Inter-Level Communication:**There may also be interactions between different hierarchical levels. Proposals or decisions from lower levels may need approval or further deliberation at higher levels, creating an interconnected governance structure.

**Security Measures and Auditing:**Implementation of robust security measures and auditing processes to ensure the integrity and security of the governance actions, protecting against unauthorized access or fraudulent activities.

*Application scenario:*

1. **Decentralized Finance (DeFi):** Implementing hierarchical DAOs in DeFi platforms can allow for multi-layer governance in lending, borrowing, and other financial services. Different levels could control risk management, interest rates, or collateral types.
2. **Token Governance:** Managing token-based projects, where the ownership of different tokens grants different levels of governance and decision-making power within the DAO.
3. **Supply Chain Management:** Utilizing different layers of governance to control various aspects of the supply chain, such as production, transportation, and distribution. Different levels can manage different parts of the chain.
4. **Non-profit and Community Organizations:** Managing community decisions within a non-profit or community-driven organization, where various levels may represent local, regional, and national chapters or committees.
5. **Governance in Online Communities:** Implementing structured governance in online communities or social platforms where different levels can control different features or moderation actions.
6. **Education and Research:** Utilizing hierarchical DAOs in educational institutions or research organizations to manage decision-making across various levels of faculty, departments, or research teams.
7. **Gaming and Entertainment:** Implementing hierarchical structures in gaming platforms or entertainment industries where different levels could oversee different aspects of game development, community management, or content creation.
8. **Real Estate and Property Management:** Utilizing different levels of governance in property management, where layers could manage different properties or segments of a real estate portfolio.
9. **Healthcare Organizations:** Hierarchical DAOs can be used in healthcare systems to manage different departments, facilities, or specialized services within the organization.
10. **Corporate Governance:** Structuring corporate governance by implementing a hierarchical DAO can allow different levels to oversee various departments, divisions, or functions within a company.

*Product design:*

In our project, the primary or root DAO serves as the top-level governance entity overseeing the entire organization. It sets the overall mission, values, and high-level decision-making processes. Sub-teams are decentralized units or sub-DAOs that focus on specific functions, projects, or geographic regions within the larger DAO. Each sub-team has its own token holders, governance rules, and decision-making processes tailored to its particular area of focus.

Tokens are used for voting and governance. The parent DAO has a native token, and each sub-team  have its own token, allowing voting rights and decision-making power. Token distribution and mechanisms for voting and proposals are designed to reflect the hierarchical structure and the relationships between the main DAO and its sub-teams. Actually, the hierarchical DAO structure can enable delegation of decision-making powers. For instance, the root DAO might delegate specific decision-making capabilities to the sub-teams or grant certain authorities to manage their affairs independently.

 A hierarchical DAO utilizing subteams promotes specialization, efficient decision-making, distributed governance, scalability, accountability, collaboration, adaptability, and optimized resource management, enhancing the overall functionality and effectiveness of the decentralized organization.
