# Pokémon Team Builder 

This project helps users build an optimal Pokémon team based on their chosen **starter Pokémon** and **region**. The system suggests a balanced team by analyzing **type advantages and weaknesses**.

## Features

- Select a **region** (Kanto, Johto, Hoenn, Sinnoh, Unova, Kalos, Alola).  
- Input your **starter Pokémon**.  
- Generate a recommended **team of six Pokémon** considering type coverage.  
- Avoids adding Pokémon from the same **evolution family** as the starter.  
- Handles missing data and invalid inputs gracefully.  

## Dataset

- Uses a Pokémon dataset containing stats, types, generation, and legendary status.  
- Temporary **evolution dictionary** used to track families (will be replaced with a dataset in later phases).  

## Usage

1. Run the notebook `Pokemon_Team_Builder.ipynb`.  
2. Enter the region and starter Pokémon when prompted.  
3. View the suggested team.  

## Future Enhancements

- Replace manual evolution dictionary with a dataset.  
- Include **Gyms and challenges** to refine recommendations.  
- Add **mockup animations** for suggested Pokémon team.
