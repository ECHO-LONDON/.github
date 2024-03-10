# Echo

Social media used to be social. Nowadays, it's a battleground for attention, with algorithms deciding what we see and when we see it. This has led to a situation where we are constantly bombarded with content that we don't care about, and we are missing out on the content that we do care about. This is a problem that we are solving with Project ECHO.

ECHO is a web3 social media aggregator platform that helps disillusioned users gain control of their own feed algorithms through "finding their people." Users connect their social media platforms and explicitly select their interests, and ECHO aggregates content across these platforms to create a customized feed.

Users engage with the content by marking what they like or dislike, enhancing the app's understanding of their preferences. This process not only refines their feed over time but also earns them tokens and progresses them towards unlocking an exclusive community feature. 

The community aspect is at the heart of ECHO, connecting users with others who share similar interests and values. This feature ensures that users not only see content that aligns with their preferences but also discover enriching content that broadens their horizons.

![1.png](./1.png)

![2.png](./2.png)

# Codebase

| Title | Link | Description |
| :---- |:---- | :---------- |
| Web application | [Link](https://github.com/ECHO-LONDON/ECHO-Web) | Full-stack webapp written in Next.js. Select interests, connect Reddit & Mastodon, and unlock Echo Community. |
| Solana smart contract | [Link](https://github.com/VenroyDEV/ECHO-BACKEND) | Smart contract to reward users of ECHO for reviewing data.
| Datasets | [Link](https://github.com/ECHO-LONDON/ECHO-DATASETS) | Datasets used for finetuning the LLM. |
| Embeddings | [Link](https://github.com/ECHO-LONDON/ECHO-Embeddings) | Finding closeness between topic and text embeddings. |
| Filecoin | [Link](https://github.com/ECHO-LONDON/ECHO-Filecoin-FVM) | Implementation of Filecoin for ECHO. |

# Challenge - Best AI Use Case for Gaming, Social or Digital Entertainment

At its heart, ECHO seeks to revolutionize the way we interact with social media. By leveraging AI, we are able to provide users with a personalized feed that is tailored to their interests, and to connect them with others who share similar interests.

![3.png](./3.png)

# Challenge - Most promising AI x Web3 Build Using Filecoin

Utilising Filecoin, our project leverages the localnet Filecoin Virtual Machine (FVM) for smart contracts, to enhance data proofing processes. Our solution leverages Filecoin for secure "Customer preference" storage and in the future complete customer profile, employing cryptographic practices for data allows for security for sensitive data related to users. As a result, Filecoin allows for the storing of a pre-processed customer dataset ready to be utilised on a machine learning model to identify profile similarities for our "community tab". This approach not only ensures privacy and security but also enables personalised user experiences. All this is based on data users provide us about their views on certain content allowing us to build a clustering model from the data we store on Filecoin.

The pre-processing system before upload is yet to be decided due to not having all parameters we want to store yet. However, when storing the data onto the blockchain we leverage Lighthouse as a median to easily instruct the FVM on the files and to extract relevant information and parameters required. In the future, have the process fully streamlined and secured in all stages via encryption and without utilising a "middle-man" like lighthouse. The tracking of file progress and publishing in this case was all done through "boost" the local host. Once published, if deals are established, Lassie Fetch mechanism was used to retrieve files but a very specific variation that considers peer-to-peer networks due to being on localnet.

Our project illustrates a comprehensive understanding of Filecoin, addressing real-world challenges with innovative solutions. Our social media aggregator filters content to deliver relevance, enhancing user interaction and feedback processes, with data securely stored on Filecoin. Our team's expertise, coupled with a clear business model, positions us for impactful execution, demonstrating our project's potential through a concise and compelling pitch.