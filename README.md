# Smart Movie Recommender: Personalizing Entertainment with Advanced Analytics

## Overview

This project implements a personalized movie recommendation system that suggests movies to users based on their preferences and viewing history. The system leverages collaborative filtering and content-based recommendation techniques to provide accurate and meaningful suggestions.

**Note**: This project is for educational purposes only.

## Features

- **Collaborative Filtering**: Recommends movies based on the preferences of similar users.
- **Content-Based Filtering**: Suggests movies by analyzing features such as genre, director, and actors.
- **Hybrid Approach**: Combines collaborative and content-based techniques for improved accuracy.
- **Scalability**: Handles large datasets efficiently.
- **Customizable**: Easily adapt the recommendation algorithm to new datasets or features.

## File Structure

1. **`main.py`**:
   - Core script for loading the dataset, training the recommendation model, and generating recommendations.

2. **Dataset**:
   - Contains movie data, user ratings, and additional metadata required for the recommendation system.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RaviKunapareddy/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
   ```

## Usage

### Train the Model
1. Ensure the dataset is in the correct directory and properly formatted.
2. Run the training script to prepare the recommendation system:
   ```bash
   python main.py --train
   ```

### Generate Recommendations
1. Provide a user ID or preferences to get movie recommendations:
   ```bash
   python main.py --recommend --user_id <USER_ID>
   ```

### Example Command
```bash
python main.py --recommend --user_id 196
```

## Example Outputs

- **Input**: User ID `196`
- **Output**:
  ```
  Recommended Movies:
  1. The Shawshank Redemption (1994)
  2. Casablanca (1942)
  3. Star Wars (1977)
  ```
- **Input**: User ID `69`
- **Output**:
  ```
  Recommended Movies:
  1. A Close Shave (1995)
  2. The Usual Suspects (1995)
  3. Rear Window (1954)
  ```


## Technologies Used

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Surprise
- **Dataset**: MovieLens dataset or custom datasets

## License

This project does not currently have a license. It is for educational purposes only, and its use or distribution should be done with the creator's consent.

## Contact

Created by **[Raviteja Kunapareddy](https://www.linkedin.com/in/ravitejak99/)**. Connect for collaboration or questions!

