# Million-Song-Dataset-Analysis  
Music Analysis and Recommendation System Development Based on the Million Song Dataset
The Million Song Dataset (MSD) is a comprehensive music dataset that integrates both 
audio and textual data. Established collaboratively by The Echo Nest and LabROSA, it has 
gradually become a cornerstone for music research and applications. The core dataset 
covers a multitude of detailed fields along with numerous audio attributes (Million Song 
Dataset, n.d.).
In addition, the MSD incorporates several sub-datasets contributed by different organizations 
and communities. Notably, there's the Taste Profile subset that logs real interactions 
between users and songs. There's also the MSD AllMusic Genre Dataset (MAGD) which 
offers detailed genre annotations for songs (Million Song Dataset, n.d.).
Before diving deep into music data research, a pivotal step is data processing. we undertook 
a preliminary exploration of each dataset. Subsequently, this report delves into the audio 
features of the MSD. These features, meticulously extracted by the Music Information 
Retrieval research group at the Vienna University of Technology, span rhythm patterns, 
statistical spectral descriptors, and more (Vienna University of Technology, 2007). Our aim is 
to unveil the intrinsic properties of these features, their interrelationships, and their 
applicability in the realm of machine learning.
Next, we shift my focus to the song recommendation system, primarily based on the Taste 
Profile dataset. Our goal is to offer personalized song recommendations for each user 
through collaborative filtering algorithms. This necessitates a profound understanding of the 
dataset's structure, its unique songs and user information, and how to efficiently train the 
collaborative filtering models.
Throughout this journey, I encountered numerous challenges. The most salient was the less 
than ideal performance of specific evaluation metrics such as Precision @ 10, NDCG @ 10, 
and Mean Average Precision (MAP) when assessing the efficacy of my collaborative filtering 
models. This hints that I might need to further refine my model. Lastly, inconsistencies and 
matching errors in some of the data presented additional hurdles for me.
