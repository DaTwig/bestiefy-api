## Quiz Service - Create Quiz

URL: https://bestiebackend.herokuapp.com/api/quizzes \
Method: POST \
Auth Required: Yes (you have to create a [token](https://github.com/TwigXx1/bestiefy-api/blob/main/auth/create.md) first!) \
Content-Type: ```application/json``` 

## Body
```json
{
    "qid": "{qid}",
    "name": "{name}",
    "questions": [
        {
            "question": "Which one is Twig's favorite food?",
            "options": [
                "Pizza 🍕",
                "Burger 🍔",
                "Sushi 🍣",
                "Taco 🌮",
                "Ramen 🍜"
            ],
            "color": 0,
            "answer": 1
        },
        {
            "question": "How long was Twig's longest relationship? 💕",
            "options": [
                "A week",
                "A month",
                "Two years",
                "And counting"
            ],
            "color": 1,
            "answer": 0
        },
        {
            "question": "What is one weird talent Twig has?",
            "options": [
                "Eyebrow dancing",
                "Epic tongue tricks",
                "Moving eyes independently",
                "Wiggling ears"
            ],
            "color": 2,
            "answer": 0
        },
        {
            "question": "What does Twig dislike the most? 😡",
            "options": [
                "Going to the dentist",
                "Slow internet",
                "Loud phone games",
                "Homework"
            ],
            "color": 3,
            "answer": 0
        },
        {
            "question": "If Twig could have one superpower which would it be?",
            "options": [
                "Flight",
                "Invisibility",
                "Teleportation",
                "Telepathy",
                "Super speed"
            ],
            "color": 4,
            "answer": 0
        },
        {
            "question": "Which celeb would Twig like as a sibling?",
            "options": [
                "Zendaya",
                "Billie Eilish",
                "Lil Nas X",
                "Dua Lipa",
                "Justin Bieber"
            ],
            "color": 5,
            "answer": 0
        },
        {
            "question": "Where does Twig spend the most time? 📱",
            "options": [
                "FYP (For you page)",
                "Feed",
                "Reels",
                "Stories",
                "Explore"
            ],
            "color": 6,
            "answer": 0
        },
        {
            "question": "Where does Twig want to travel the most? 🌎",
            "options": [
                "Paris",
                "New York",
                "Bali",
                "Tokyo",
                "Tulum"
            ],
            "color": 7,
            "answer": 0
        },
        {
            "question": "How tall is Twig?",
            "options": [
                "Less than 5'3ft (160cm)",
                "5'4ft (161cm) - 5'8ft (172cm)",
                "5'9ft (173cm) - 5'11ft (181cm)",
                "6'0ft (182cm) and up"
            ],
            "color": 0,
            "answer": 0
        },
        {
            "question": "When is Twig's birthday? 🎂",
            "options": [
                "September 9th",
                "July 7th",
                "March 10th",
                "February 24th",
                "September 19th"
            ],
            "color": 1,
            "answer": 0
        }
    ],
    "langloc": "NA-EN",
    "creator": "{put whatever I guess lmao}"
}
```

## Answers

Each question shows an answer that has a 0,1,2,3... \
Here's a example on which one is the answer:

## Answer Guide
```
 {
            "question": "How tall is Twig? (this isn't an actual fact)",
            "options": [
          (0)      "Less than 5'3ft (160cm)",           // This is 0 which is correct
          (1)      "5'4ft (161cm) - 5'8ft (172cm)",      // This is 1 which is wrong
          (2)      "5'9ft (173cm) - 5'11ft (181cm)",      // This is 2 which is wrong
          (3)      "6'0ft (182cm) and up"                  // This is 3 which is wrong
            ],
            "color": 0,
            "answer": 0 // This shows what number is right, look at options
        }

