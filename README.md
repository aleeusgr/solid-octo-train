**Decentralized Code Collaboration with Cardano-Node and Radicle**
===========================================================

**Introduction**
---------------

This proof of concept project demonstrates the integration of Cardano-node with Radicle, a decentralized, open-source, peer-to-peer code collaboration stack built on Git. The goal of this project is to contribute to the discussion on decentralizing code collaboration within the Cardano community, promoting a self-sovereign collaboration network.

**Motivation**
------------

The Cardano community's current reliance on centralized platforms like GitHub poses risks to the community's autonomy and decentralization principles. By integrating Cardano-node with Radicle, we can enhance the security and autonomy of our code collaboration processes, reducing reliance on centralized platforms and mitigating associated risks.

**About Radicle**
----------------

Radicle is a decentralized code collaboration platform that allows users to host and manage Git repositories in a peer-to-peer manner. Unlike centralized platforms, Radicle does not rely on a single entity to control the network, ensuring that users are in full control of their data and workflow.

**Project Overview**
------------------

This proof of concept demonstrates the following:

1. **Cardano-Node Integration**: We integrate Cardano-node with Radicle, enabling the seeding of code repositories via Cardano-node.
2. **Decentralized Code Collaboration**: We showcase the potential of Radicle as a decentralized code collaboration platform for the Cardano community.
3. **Reward Mechanism**: We explore the design of a reward mechanism to incentivize community members to seed code repositories via Cardano-node.

**Getting Started**
-----------------

To get started with this project, follow these steps:

1. Clone the repository: `git@github.com:aleeusgr/solid-octo-train.git`
2. Start the Cardano-node: `nix run .#cardano-node -- run    --topology ../preprod/topology.json    --database-path ../preprod/db    --socket-path ../preprod/db/node.socket    --host-addr 0.0.0.0    --port 3000    --config ../preprod/config-bp.json`
3. Start the Radicle node: `rad node start`
4. run main script: `$./main.sh`
5. trigger the event in the log: `rad node status`
6. the script produces the output of `cardano-node query tip` command.

**Contributing**
---------------

This project is a proof of concept, and we invite the Cardano community to contribute to the discussion and development of decentralized code collaboration solutions. If you're interested in contributing, please fork the repository and submit a pull request.

**License**
-------

This project is licensed under the Apache-2.0 license.

**Acknowledgments**
----------------

We acknowledge the support of the Cardano community and the Radicle team in making this project possible.
