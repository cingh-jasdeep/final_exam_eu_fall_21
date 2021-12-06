## Final Exam Fall 2021, Mobile Apps
#### Eternal University, Baru Sahib


Waheguru Ji Ka Khalsa
Waheguru Ji Ki Fateh ji

Welcome to the final exam of Mobile Apps.
This exam/exercise assumes you are familiar with [Topics](https://docs.google.com/document/d/181pcbvjMfZyU6oBY4mit2E8GftNrWmQucVXWMX6wN9c/edit?usp=sharing) covered in class for Fall 2021 Semester at Eternal University, Baru Sahib.

We shall be designing and implementing a news app, named as 'Good News App' :)
Apart from making the reader happy,
in the process of making this app, you will apply concepts you covered in class.

This is an ***open internet*** test.
Apart from communicating to your fellow students (which is not allowed), 
you are encouraged to lookup Lecture Notes and other sources online including docs.flutter.dev 


So with God's grace, let's get started.
You are given a series of steps, feel free to ask your **invigilator** if you have any doubts understanding any step.

### Step 1 - Create project
- First create a new Flutter 'Application' inside Visual Studio Code.
and name it 'good_news_app'
[REFERENCE LINK](https://docs.flutter.dev/development/tools/vs-code#creating-a-new-project)


### Step 2 - Add app icon
- Add android app icon using image provided [app_icon.png](app_icon.png)
and [easyappicon](https://easyappicon.com/) (as you did in your 'I am Rich' app)

### Step 3 - Copy assets
- Copy [fonts](fonts) and [images](images) folder to your project directory,
as these contain assets needed for the app.

### Step 4 - Create a StatefulWidget - `NewsPage`
- Create a new file, `news_page.dart` inside your project's `lib` folder.

- Inside this file, create a new `StatefulWidget` (using VSCode [snippets](https://docs.flutter.dev/development/tools/vs-code#snippets))
named `NewsPage` (you may need to import the material library to for `StatefulWidget` to be recognized)

- Set `NewsPage` as `home` of your MaterialApp in `main.dart` (Be sure to import files correctly) (you may refer to the BMI and Quizzler app to see how you did this)

### Step 5 - Design NewsPage layout
- Use your knowledge of layout widgets (Columns, Rows, Scaffold, AppBar, Expanded etc.. like you did in Dicee, BMI Calculator)
design a layout for the `NewsPage` widget as given in the Google Drawing link below
https://docs.google.com/drawings/d/1q3afjuS3paoDp-6t46MqTd5hgP6eluNFRDEYUFKJ8VM/edit?usp=sharing

- You may find it useful to **run** the app and design side-by-side, taking advantage of *HotReload* and *HotRestart*.

- For mock image and text
you can use
`'images/Disabilities_Act.jpg'` (Asset Image) and
```
'TNIE Impact: Sivakasi Elwin Center gets disabled friendly toilets
Toilets were constructed after The New Indian Express had highlighted the needs of the school on September 19 and raised the question of whether the funds would reach the cause.
By Azeefa Fathima
Express News Service
VIRUDHUNAGAR: In less than two months after Collector J Meghanatha Reddy passed the proceedings for the construction of two disabled-friendly toilets, the funds have found its way for the same. Collector opened two disabled-friendly toilets under the \'Udhayam\' scheme in the CSI school for Elwin Centre in Sivakasi for use on the occasion of World Disability Day here on Friday.

Toilets were constructed after The New Indian Express had highlighted the needs of the school on September 19 and raised the question of whether the funds would reach the cause. It looks like the universe has indeed conspired in helping them in achieving their needs.

Speaking at the inauguration event, the collector said though he was exposed to the issues of Persons with Disabilities (PwDs) through his friends, difficulty in using a toilet did not come into his thought up until it a 16-year-old girl in a pension camp at the collectorate raised it.

"Normally toilets at our houses would be small and cannot be easily accessed by PwDs. After the girl explained their plight, I wanted to do something about this, and we devised the \'Udhayam\' scheme. Though we will not be able to construct toilets for everyone immediately, we are doing it in a phased manner based on CSR funds and other fund availability, prioritising women and girls," he said.  

He further said under the initiative it has been aimed to build at least 100 toilets by the end of this year. Speaking about the need of the school, he said that when the school approached him, though there was no fund at hand, he had made arrangements from his discretionary funds.

The funds for two other toilets under construction is sponsored by a private sponsor, he added. Stating a saying, he said, "When you want something, all the universe conspires in helping you to achieve it, and I wanted to do this for the differently-abled people. I got in touch with the like-minded people who supported me in taking the project forward," he said.

School correspondent M Dayalan Barnabas demanded three things during the function: a paver block road leading to the school; include the widowed women in the school in the scheme where free goats are distributed by the state government and include Elwin Centre in \'Adult Project\' under the PwD welfare department as nearly 50 adult PwDs are residing in the school. Collecter assured to take action.

Backstory

The Elwin Centre, located in Sivakasi\'s Satchiyapuram was established in 1980 by Selvabai and her husband Reverend Thavaraj David. The school is now working under the model of self-sustenance with limited funding. The school aims to translate its financial model into the lives of its children. As part of the self-sustenance project, they bought 50 country chickens and reared them. "Everything, from feeding the chicken to cleaning the coops, was done by our children. The money coming from the rearing is re-invested in similar ventures.

During the earlier interaction with The New Indian Express, they had highlighted two issues: a crunch in funds despite the self-sustenance model and well-wishers; and the lack of disability-friendly toilets for the children who also have physical disabilities.

When the latter issue was highlighted to the collector, he had immediately conducted inspections, following which Rs 94,000 was sanctioned in the first phase for the construction of two toilets and mobilised funds through private sponsor for the construction of another two.

Earlier, the district officials, led by the collector, created a project named Udhayam to build accessible toilets in their houses for PwDs, in the district.

\nhttps://www.newindianexpress.com/good-news/2021/dec/04/tnie-impact-sivakasi-elwin-center-getsdisabled-friendly-toilets-2391706.html'
```

- Please note to use asset images and fonts, you may need to import them in `pubspec.yaml` (As done in MICard and Magic8Ball app)





