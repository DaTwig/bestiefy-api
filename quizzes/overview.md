## Quiz Service - Overview Quiz

URL: https://bestiebackend.herokuapp.com/api/quizzes/{qid} \
Method: GET \
Auth Required: Yes (you have to create a [token](https://github.com/TwigXx1/bestiefy-api/blob/main/auth/create.md) first!)

## Headers

Authorization: Bearer ```{access_token}```

## Example Response 

```json
{
    "qid": "IULUV1",
    "name": "Balls",
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
    "creator": "BALLLS"
}
```

## Answers

For information about answers go [here](https://github.com/TwigXx1/bestiefy-api/blob/main/quizzes/create.md#answer-guide)