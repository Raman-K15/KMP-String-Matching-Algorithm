# KMP-String-Matching-Algorithm
### This algorithm is one of the many algorithms used to find the similar patterns in the two strings. 
### One of the major application of this algorithm is- It could be used to identify the patterns, even in fingeprints! 
### Provided a standard fingerprint, we can identify a pattern in it. Now, since we have many potential fingerprints which can match with the standard fingerprint, We are able to design a pattern from all these fingerprints. Now we have two patterns- One is standard pattern while other is not. We can use this algorithm to identify the similarity in standard fingerprint and all the potential fingerprints. One which has all the matching patterns, we can declare it as an exact match.
### KMP algorithm has worst case time complexity O(n). This is much lesser than the time complexity of naive approach which is O(m(n-m+1)).
### Attached are some test cases
#### 1. When there is a match
####![image](https://user-images.githubusercontent.com/113305888/205102262-2cd11898-c902-4521-b656-75abb19b03ab.png)
#### 2. When the pattern is smaller than the standard
####![image](https://user-images.githubusercontent.com/113305888/205102464-473b1943-6f83-4d22-8447-9f43d8202dd7.png)
#### 3. When there is no match at all
####![image](https://user-images.githubusercontent.com/113305888/205102588-0c79ed8c-2afc-47b9-bee1-f5ff18fe6684.png)
