###Andrew Pastor
___

#####Contacts for communication:

* *Phone: +375295827421;*
* *Email: pastorandrew91@gmail.com;*
* *Discord: AndrewPastor(@andrewpastor);*

___

#####Personal statement:
**Main goal:** to become a quality full-stack developer.


I am balanced, non-conflict, have high moral qualities, positively influence the socio-psychological climate in the team. I strive to learn new areas of activity, constantly improve my skills.
Since 2016, I have been working in the laboratory of the research part of BSUIR as a junior researcher. I have a high level of qualification in the profile of the laboratory.

**Education:**
2016 - graduated from BSUIR with a degree in metrology engineer.
2018 - graduated from the master's program with the title of master of technical sciences.
2021 - completed the "Fundamentals of Programming" courses on the Stepik educational platform.

**Skills:**
C# - basic knowledge using OOP and ASP.NET Core;
version control system Git - confident user;
Microsoft Visual Studio, Visual Studio Code - confident user.

**English language:**
2020 - completed English language courses at BSUIR at the level Pre-Intermediate (received a certificate); 
2021 - for one semester at BSUIR lectured to foreign students in English.

**Code example:**

```public class Kata
{
  public static string DuplicateEncode(string word)
  {
    string wo = word.ToLower();
            string res = null;
            int cnt = 0;
            for (int i = 0; i < wo.Length; i++)
            {
                char a = wo[i];
                for (int j = 0; j < wo.Length; j++)
                {
                    char b = wo[j];
                    if (a == b)
                    {
                        cnt++;
                    }
                }
                if (cnt > 1)
                {
                    res = res + ")";
                }
                else res = res + "(";

                cnt = 0;
            }

            word = res;
    return word;
  }
}
```
[My first project](https://github.com/AndrewPastor/rsschool-cv.git)