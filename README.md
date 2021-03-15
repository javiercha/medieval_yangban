# Medieval Yangban

In this space, I share the Jupyter notebooks and data sets used in my digital historical research of the medieval Korean yangban. This monograph-length study is an extension and data-heavy treatment of the _problématique_ covered in the article "[To Build a Centralizing Regime: Yangban Aristocracy and Medieval Patrimonialism](https://doi.org/10.1353/seo.2019.0003)."

The data sources are from the following:
* Lee Jaeok Munkwa Nodes: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/1_1-%EA%B3%BC%EA%B1%B0_%ED%95%A9%EA%B2%A9%EC%9E%90_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EB%AC%B8%EA%B3%BC).xlsx
* Lee Jaeok Munkwa Kinship Edges: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/2_1-%EC%B9%9C%EC%86%8D_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EB%AC%B8%EA%B3%BC).xlsx
* Lee Jaeok Mukwa Nodes: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/1_2-%EA%B3%BC%EA%B1%B0_%ED%95%A9%EA%B2%A9%EC%9E%90_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EB%AC%B4%EA%B3%BC).xlsx
* Lee Jaeok Mukwa Kinship Edges: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/2_2-%EC%B9%9C%EC%86%8D_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EB%AC%B4%EA%B3%BC).xlsx
* Lee Jaeok Chosŏn Saengwon Nodes: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/1_3-%EA%B3%BC%EA%B1%B0_%ED%95%A9%EA%B2%A9%EC%9E%90_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EC%83%9D%EC%9B%90).xlsx
* Lee Jaeok Chosŏn Chinsa Nodes: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/1_3-%EA%B3%BC%EA%B1%B0_%ED%95%A9%EA%B2%A9%EC%9E%90_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EC%A7%84%EC%82%AC).xlsx
* Lee Jaeok Chosŏn Sama (Saengwon + Chinsa) Kinship Edges: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/2_3-%EC%B9%9C%EC%86%8D_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EC%82%AC%EB%A7%88).xlsx
* Lee Jaeok Koryŏ Munkwa Nodes: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/1_5-%EA%B3%BC%EA%B1%B0_%ED%95%A9%EA%B2%A9%EC%9E%90_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EA%B3%A0%EB%A0%A4%EB%AC%B8%EA%B3%BC).xlsx
* Lee Jaeok Koryŏ Munkwa Kinship Edges: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/2_4-%EC%B9%9C%EC%86%8D_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EA%B3%A0%EB%A0%A4%EB%AC%B8%EA%B3%BC).xlsx
* Lee Jaeok Koryŏ Sama Nodes: http://dh.aks.ac.kr/~sonamu5/sndm/1_raw_data/1_6-%EA%B3%BC%EA%B1%B0_%ED%95%A9%EA%B2%A9%EC%9E%90_%EB%8D%B0%EC%9D%B4%ED%84%B0(%EA%B3%A0%EB%A0%A4%EC%82%AC%EB%A7%88).xlsx
* Academy of Korean Studies UCI and Exam ID: web scraped from http://people.aks.ac.kr/front/dirSer/exm/exmKingExmList.aks?classCode=MN&className=%EB%AC%B8%EA%B3%BC&isEQ=true&kristalSearchArea=B
* Man'gabo Genealogy Nodes: http://dh.aks.ac.kr/~sonamu5/sndm/2_semantic_data/3_%EB%A7%8C%EA%B0%80%EB%B3%B4_Node_List.xlsx
* Man'gabo Genealogy Edges: http://dh.aks.ac.kr/~sonamu5/sndm/2_semantic_data/4_%EB%A7%8C%EA%B0%80%EB%B3%B4_Link_List.xlsx
* LNIS Mansŏng Taedongbo Genealogy: http://lnis.kr/

The Python notebooks extract a subset of genealogical information pertaining to every exam degree holder up to three generations above and below from Man'gabo and Mansŏng Taedongbo.

The temporal coverage is from 958 to 1609, defined by ego's year of birth or year in which he attained an exam degree. My data analysis is limited to 1567, or the death of King Munjong (r. 1545-1567). Any results concerning egos in the data set after 1567 should consider the 1609 cutoff point.
