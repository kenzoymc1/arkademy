function myBiodata(biodata){
  let biodataObj = {
    "name": 'Arwy Syahputra Siregar',
    "age" : "22",
    "address": 'Medan',
    "hobbies": [
      'Coding', 'Reading' ],
    "is_married": false,
    "school": {
      "highSchool": 'MAN 2 Lebak',
      "university": 'UNPAM',
	"YearsIn" : "2014",
        "YearsOut" : "2019",
	"Majoring" : 'Civil Engineering'
    },
    "skill": [
      {
        "HTML5": 'beginner',
        "Javascript":'Beginner',
        "Java": 'Advanced',
        "xml": 'advanced',
        "Bootstrap": "95 %",
        "GIT": "80 %",
      },
     {
         "interest_in_coding" : true,
      }
    ]
  }

  return biodataObj
}
console.log(myBiodata('arwy'));


//fungsi JSON pada Rest Api adalah sebagai format untuk mentransmisikan data dari WEB API(server) ke client atau sebaliknya