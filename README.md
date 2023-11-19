# 💫 About Me:
I am Sathyabama V currently pursuing B Tech Information Technology<br>I’m currently working on web development<br>I’m looking to collaborate on open source projects and also efficiently with colleagues<br>And i am also eager to learn upcoming technological stacks


## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/sathyabama-v-722877233) 

# 💻 Tech Stack:
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=SathyabamaV29062002&theme=vue&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=SathyabamaV29062002&theme=vue&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=SathyabamaV29062002&theme=vue&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=SathyabamaV29062002&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
[![](https://visitcount.itsvg.in/api?id=SathyabamaV29062002&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->



SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";

CREATE TABLE `movie` (
  `ID` int(100) NOT NULL,
  `M_name` varchar(50) NOT NULL,
  `Director` varchar(50) NOT NULL,
  `Actor` varchar(100) NOT NULL,
  `M_img` varchar(100) NOT NULL,
  `Music` varchar(50) NOT NULL,
  `Rel_yr` varchar(20) NOT NULL,
  `Lang` varchar(20) NOT NULL,
  `gener` varchar(20) NOT NULL,
  `Rating` float NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;


INSERT INTO `movie` (`ID`, `M_name`, `Director`, `Actor`, `M_img`, `Music`, `Rel_yr`, `Lang`, `gener`, `Rating`) VALUES
(19, 'Vikramvxcvdfgdfgdfgdfgfgdfgdfgfgdfgdfgdfgdfgdfgdfg', 'Logesh', 'Kamal, VJS', '', 'Anirudh', '2022', 'Tamil', 'Action', 4.5),
(22, 'ss', 'dsfsd', 'dsfsdfsd dfvfvfdv dfvdfvf', '', 'dfvfdv', '2022', 'Malayalam', 'Fantasy', 3);


ALTER TABLE `movie`
  ADD PRIMARY KEY (`ID`);
  
ALTER TABLE `movie`
  MODIFY `ID` int(100) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=23;
COMMIT;
