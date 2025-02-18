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
  
  <a href="https://www.linkedin.com/in/kyle-c-lai/" style="text-decoration:none">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/81/LinkedIn_icon.svg" alt="Kyle Lai's LinkedIn Profile" height="30" width="30" style="display:block">
  </a>
	
  <a href="mailto: kcklaius@gmail.com" style="text-decoration:none">
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Gmail_icon_%282020%29.svg" alt="Kyle Lai's Gmail" height="30" width="30" style="display:block">
  </a> 

  <a href="https://hub.docker.com/u/kyleclai" style="text-decoration:none">
     <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Docker-svgrepo-com.svg" alt="Kyle Lai's dockerhub Profile" height="35" width="35" style="display:block">
  </a>

</p>
