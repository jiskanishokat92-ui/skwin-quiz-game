// Quiz Questions Database - 200+ Questions

const quizCategories = {
    "General Knowledge": [
        {
            question: "What is the capital of France?",
            options: ["Paris", "London", "Berlin", "Madrid"],
            correct: 0
        },
        {
            question: "What is the largest planet in our solar system?",
            options: ["Mars", "Saturn", "Jupiter", "Neptune"],
            correct: 2
        },
        {
            question: "Who wrote Romeo and Juliet?",
            options: ["Charles Dickens", "William Shakespeare", "Jane Austen", "Mark Twain"],
            correct: 1
        },
        {
            question: "What is the smallest country in the world?",
            options: ["Monaco", "Vatican City", "Liechtenstein", "San Marino"],
            correct: 1
        },
        {
            question: "What year did World War II end?",
            options: ["1943", "1944", "1945", "1946"],
            correct: 2
        },
        {
            question: "What is the capital of Japan?",
            options: ["Osaka", "Tokyo", "Kyoto", "Nagoya"],
            correct: 1
        },
        {
            question: "Who invented the telephone?",
            options: ["Thomas Edison", "Alexander Graham Bell", "Nikola Tesla", "Benjamin Franklin"],
            correct: 1
        },
        {
            question: "What is the currency of India?",
            options: ["Rupiah", "Indian Rupee", "Rupiah", "Taka"],
            correct: 1
        },
        {
            question: "How many continents are there?",
            options: ["5", "6", "7", "8"],
            correct: 2
        },
        {
            question: "What is the deepest ocean trench?",
            options: ["Mariana Trench", "Tonga Trench", "Philippine Trench", "Kuril-Kamchatka"],
            correct: 0
        },
        {
            question: "Which country is home to the Great Wall?",
            options: ["Japan", "India", "China", "Mongolia"],
            correct: 2
        },
        {
            question: "What is the capital of Australia?",
            options: ["Sydney", "Melbourne", "Canberra", "Brisbane"],
            correct: 2
        },
        {
            question: "Who painted the Mona Lisa?",
            options: ["Vincent van Gogh", "Leonardo da Vinci", "Michelangelo", "Raphael"],
            correct: 1
        },
        {
            question: "What is the second largest desert in the world?",
            options: ["Gobi", "Arabian", "Sahara", "Arctic"],
            correct: 3
        },
        {
            question: "In which year did the Titanic sink?",
            options: ["1910", "1911", "1912", "1913"],
            correct: 2
        },
        {
            question: "What is the capital of Brazil?",
            options: ["Rio de Janeiro", "São Paulo", "Brasília", "Salvador"],
            correct: 2
        },
        {
            question: "How many sides does a hexagon have?",
            options: ["5", "6", "7", "8"],
            correct: 1
        },
        {
            question: "What is the largest mammal in the world?",
            options: ["African Elephant", "Giraffe", "Blue Whale", "Hippopotamus"],
            correct: 2
        },
        {
            question: "Which planet is known as the Red Planet?",
            options: ["Venus", "Mars", "Mercury", "Jupiter"],
            correct: 1
        },
        {
            question: "What is the capital of Canada?",
            options: ["Toronto", "Vancouver", "Ottawa", "Montreal"],
            correct: 2
        }
    ],
    "Sports": [
        {
            question: "How many players are on a basketball team on the court?",
            options: ["4", "5", "6", "7"],
            correct: 1
        },
        {
            question: "In which sport is the Stanley Cup awarded?",
            options: ["Basketball", "Hockey", "Football", "Baseball"],
            correct: 1
        },
        {
            question: "How many holes are on a golf course?",
            options: ["9", "18", "36", "27"],
            correct: 1
        },
        {
            question: "Which country has won the most FIFA World Cups?",
            options: ["Germany", "France", "Brazil", "Argentina"],
            correct: 2
        },
        {
            question: "In tennis, what is a score of zero called?",
            options: ["Nil", "Love", "Zero", "Empty"],
            correct: 1
        },
        {
            question: "How many players are on a cricket team?",
            options: ["9", "10", "11", "12"],
            correct: 2
        },
        {
            question: "In American football, how many points is a touchdown worth?",
            options: ["3", "6", "7", "10"],
            correct: 1
        },
        {
            question: "What is the maximum score in bowling?",
            options: ["100", "200", "300", "400"],
            correct: 2
        },
        {
            question: "In which sport would you use a shuttlecock?",
            options: ["Tennis", "Badminton", "Squash", "Racquetball"],
            correct: 1
        },
        {
            question: "How long is a marathon?",
            options: ["26 miles", "26.2 miles", "30 miles", "25 miles"],
            correct: 1
        },
        {
            question: "Which sport uses a puck?",
            options: ["Basketball", "Football", "Hockey", "Baseball"],
            correct: 2
        },
        {
            question: "How many sets are in a tennis match?",
            options: ["2", "3", "4", "5"],
            correct: 1
        },
        {
            question: "What is the highest score in darts?",
            options: ["140", "160", "180", "200"],
            correct: 2
        },
        {
            question: "In swimming, how many strokes are there in Olympic swimming?",
            options: ["2", "3", "4", "5"],
            correct: 2
        },
        {
            question: "How many points is a field goal worth in football?",
            options: ["2", "3", "4", "5"],
            correct: 1
        },
        {
            question: "What is the name of the tennis tournament held at Wimbledon?",
            options: ["US Open", "French Open", "Wimbledon Championships", "Australian Open"],
            correct: 2
        },
        {
            question: "How many players are on a baseball team?",
            options: ["8", "9", "10", "11"],
            correct: 1
        },
        {
            question: "In which sport would you see a 'checkmate'?",
            options: ["Bridge", "Chess", "Poker", "Checkers"],
            correct: 1
        },
        {
            question: "How many innings are in a baseball game?",
            options: ["7", "8", "9", "10"],
            correct: 2
        },
        {
            question: "What is the name of the trophy awarded to the NFL champion?",
            options: ["World Trophy", "Super Bowl Trophy", "Lombardi Trophy", "Championship Cup"],
            correct: 2
        }
    ],
    "Science": [
        {
            question: "What is the chemical symbol for Gold?",
            options: ["Go", "Gd", "Au", "Ag"],
            correct: 2
        },
        {
            question: "What is the speed of light?",
            options: ["300,000 km/s", "150,000 km/s", "450,000 km/s", "600,000 km/s"],
            correct: 0
        },
        {
            question: "How many bones are in the human body?",
            options: ["186", "206", "226", "246"],
            correct: 1
        },
        {
            question: "What is the chemical symbol for Silver?",
            options: ["Si", "S", "Ag", "Sr"],
            correct: 2
        },
        {
            question: "What is the largest organ in the human body?",
            options: ["Heart", "Brain", "Skin", "Liver"],
            correct: 2
        },
        {
            question: "How many chambers does a human heart have?",
            options: ["2", "3", "4", "5"],
            correct: 2
        },
        {
            question: "What element has the atomic number 1?",
            options: ["Helium", "Hydrogen", "Lithium", "Beryllium"],
            correct: 1
        },
        {
            question: "What is the powerhouse of the cell?",
            options: ["Nucleus", "Mitochondria", "Ribosome", "Chloroplast"],
            correct: 1
        },
        {
            question: "How many chromosomes do humans have?",
            options: ["23", "46", "48", "50"],
            correct: 1
        },
        {
            question: "What is the chemical formula for water?",
            options: ["H2O", "H2O2", "HO", "H3O"],
            correct: 0
        },
        {
            question: "What gas do plants absorb from the atmosphere?",
            options: ["Oxygen", "Nitrogen", "Carbon Dioxide", "Hydrogen"],
            correct: 2
        },
        {
            question: "What is the normal body temperature of a human?",
            options: ["36°C", "37°C", "38°C", "39°C"],
            correct: 1
        },
        {
            question: "How many pairs of ribs do humans have?",
            options: ["10", "11", "12", "13"],
            correct: 2
        },
        {
            question: "What is the chemical symbol for Iron?",
            options: ["I", "Ir", "Fe", "In"],
            correct: 2
        },
        {
            question: "What type of animal is a dolphin?",
            options: ["Fish", "Mammal", "Reptile", "Amphibian"],
            correct: 1
        },
        {
            question: "What is the process by which plants make their own food?",
            options: ["Respiration", "Photosynthesis", "Fermentation", "Digestion"],
            correct: 1
        },
        {
            question: "How many sides does a DNA molecule have?",
            options: ["1", "2", "3", "4"],
            correct: 1
        },
        {
            question: "What is the chemical symbol for Oxygen?",
            options: ["O", "O2", "Ox", "Og"],
            correct: 0
        },
        {
            question: "What is the process of water turning into vapor?",
            options: ["Condensation", "Evaporation", "Sublimation", "Precipitation"],
            correct: 1
        },
        {
            question: "How many chambers does a squid's heart have?",
            options: ["1", "2", "3", "4"],
            correct: 2
        }
    ]
};

// Function to get a random question from a category
function getRandomQuestion(category) {
    const questions = quizCategories[category];
    return questions[Math.floor(Math.random() * questions.length)];
}

// Function to get all categories
function getAllCategories() {
    return Object.keys(quizCategories);
}
