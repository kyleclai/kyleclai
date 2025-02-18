<h2 align="center">About Me 🗺️</h2> 

```Python
class Bio:
    def __init__(self):
        self.data = {
            "- 🌱 I’m currently learning":    "Generative AI, Machine Learning, and Neuro-inspired AI",
            "- ❔ I’m looking for help with": "Exploring innovative uses of ML in bioinformatics and AI",
            "- 📚 I'm interested in":         "AI, Bioinformatics (Network Motifs), Radiogenomics, "
                                              "Interpretable Models (XAI), Generative Models, "
                                              "Decentralized Learning, Mathetmatics!"
        }


def get_bio():
    return Bio().data

if __name__ == "__main__":
    bio_data = get_bio()
    
    print("About Me 🗺️")
    print("\n".join([f"{k}: {v}" for k, v in bio_data.items()]))
```
<h2 align="center">You can reach me at </h2>

<p align="center">
  
  <a href="https://www.linkedin.com/in/kyle-c-lai/">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="Samin Mahdipour's LinkedIn Profile" height="30" width="30" style="display:block">
  </a>
	
  <a href="mailto: kcklaius@gmail.com">
    <img src="https://simpleicons.org/icons/gmail.svg" alt="Kyle Lai's Gmail" height="30" width="30" style="display:block">
  </a> 

  <a href="https://hub.docker.com/u/kyleclai">
     <img src="https://simpleicons.org/icons/docker.svg" alt="Kyle Lai's dockerhub Profile" height="35" width="35" style="display:block">
  </a>

</p>
