# IUS-Hacktoberfest

A collection of data points and a data visualization model for the 2019 Hacktoberfest at IUS

## How do I get my name added

The format for your new addition should look like this: (TODO)
First: Open the data.json file. You should see something simliar to this:

```json
{
    "people":
    [
    {
        "name": "Zach Bouvier",
        "major": "Computer Science - Math and Science",
        "role": "Student",
        "year": "Freshman",
        "profile": "https://github.com/zbouvier",
        "optionalInformation":
        {
            "email": "zbouvier@iu.edu",
            "favoriteLanguages": ["Python", "Chef", "F#"],
            "hobbies": ["Long walks on the beach", "Yelling at everybody", "Big Data"]
        }
    },
    {
        "name": "Chris Sexton",
        "major": "Computer Science",
        "role": "Professor",
        "year": "",
        "profile": "https://github.com/chrissexton",
        "optionalInformation":
        {
            "email": "",
            "favoriteLanguages": ["Go", "F#"],
            "hobbies": ["Cats", "Giving Hard Homework Assignments", "Reddit"]
        }
    }
    ]
}
```

Secondly, you want to add a comma after the previous person



```json
{
    "people":
    [
    {
        "name": "Zach Bouvier",
        "major": "Computer Science - Math and Science",
        "role": "Student",
        "year": "Freshman",
        "profile": "https://github.com/zbouvier",
        "optionalInformation":
        {
            "email": "zbouvier@iu.edu",
            "favoriteLanguages": ["Python", "Chef", "F#"],
            "hobbies": ["Long walks on the beach", "Yelling at everybody", "Big Data"]
        }
    },
    {
        "name": "Chris Sexton",
        "major": "Computer Science",
        "role": "Professor",
        "year": "",
        "profile": "https://github.com/chrissexton",
        "optionalInformation":
        {
            "email": "",
            "favoriteLanguages": ["Go", "F#"],
            "hobbies": ["Cats", "Giving Hard Homework Assignments", "Reddit"]
        }
    },  <-------------------------------- like this
    ]
}
```

Thirdly, copy the code of the previous person, and edit it to your heart's content. Like so:

```json
{
    "people":
    [
    {
        "name": "Zach Bouvier",
        "major": "Computer Science - Math and Science",
        "role": "Student",
        "year": "Freshman",
        "profile": "https://github.com/zbouvier",
        "optionalInformation":
        {
            "email": "zbouvier@iu.edu",
            "favoriteLanguages": ["Python", "Chef", "F#"],
            "hobbies": ["Long walks on the beach", "Yelling at everybody", "Big Data"]
        }
    },
    {
        "name": "Chris Sexton",
        "major": "Computer Science",
        "role": "Professor",
        "year": "",
        "profile": "https://github.com/chrissexton",
        "optionalInformation":
        {
            "email": "",
            "favoriteLanguages": ["Go", "F#"],
            "hobbies": ["Cats", "Giving Hard Homework Assignments", "Reddit"]
        }
    },
        {
        "name": "John Smith",
        "major": "Informatics",
        "role": "Student",
        "year": "Senior",
        "profile": "https://github.com/<yourGithubUsername>",
        "optionalInformation":
        {
            "email": "yourIUemail@iu.edu",
            "favoriteLanguages": ["Python", "JavaScript"],
            "hobbies": [""]
        }
    },  
    ]
}
```

Please note that there **is** no comma at the end of your new person. Technically this makes it not valid JSON, however in order to allow for easy merges, the program accounts for the trailing comma at the end.
