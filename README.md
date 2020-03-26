# IPFS-wiki
**What is IPFS? (Inter-Planetary File System)**

This is a peer-peer network and a content-based system. Today’s web is mostly centralized. Eg:- Say that we want to download a photo from google. Google image search will give all the related links for the available to the photos. So let’s say we want image A. Google will give a link for that. If the source goes offline we won’t be able to get that image. This is a centralized system.

  

In IPFS it is a content-based distributed system. If we take the same above example, we want to download image A. So several people might already have this image. So the link which we have to download is based on the content. There is no actually one owner for this content. Even though one owner(source) goes offline the link is still working and the content is still available for download.
![Diagram](https://raw.githubusercontent.com/janethavi/IPFS-wiki/dev/Images/http-vs-ipfs.jpg)
  

The following diagram will elaborate more on this idea.

**Advantages**
-   Content will get loaded faster.
    
-   Even though one source is not available the content is still available with other sources and the link for the source will be the same.
    
-   By using the hash of the content we exactly know what we are looking for. In a centralized system, we can provide some different content even though the link says something else. Eg:- we can get a dog’s photo even though the link says its a cat. But in IPFS the content hash is generated, so we get the exact cat which we were looking for.

**Disadvantages**
-   IPFS consumes a lot of bandwidth which is not appreciated by metered internet users.
    
-   IPFS currently is used by tech enthusiast and normal people don’t tend to set up their own node, which leads to a shortage of nodes on the network.

**How IPFS Works?**

Files are stored in Objects. One object stores up to 256KB of data. Also, this object stores links to other IPFS objects. If there is a large file such as an image or a video, that file is split into, multiple objects. Afterwards, the system will create an empty object and that empty object will contain links to those objects multiple objects. Then the content hash will be taken as the URL. If the content changes this hash will also change. As a result, the URL will also be changed.

  

**File coin**

The people who invented IPFS invented file coin. If you have free space in your hard disk you can rent it out to others and make money out of that. The system will make sure to create several multiple copies of the content in other systems as well. So the content will be available most of the time. You will be paid for amount of time period of sharing the storage.