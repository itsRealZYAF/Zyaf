```py
class itsRealZYAF:
    def __init__(self):
        self.user_socials = []
    
    def socials(self, socials: list):
        for item in socials:
            if item == 'twitter':
                self.user_socials.append('twitter : itsRealZYAF')
                
            elif item == 'instagram':
                self.user_socials.append('instagram : zyafhack_')

            elif item == 'discord':
                self.user_socials.append('discord : @Zyaf#0001')
                
            else:
                self.user_socials.append(f'{item} : unknown')
        return self.user_socials

    def bio(self):
        name      : str = "Zyaf"
        age       : str = "17"
        birthday  : str = "08/10/2003"
        status    : list = ["student", "developer"]
        languages : list = ["french", "english", "spanish"]
        return name, age, birthday, status, languages

if __name__ == "__main__":
    client = itsRealZYAF()
    socials = client.socials(['twitter', 'instagram', 'discord'])
    bio = client.bio()
    for i in socials:
        print(i)
    print(bio)
```
