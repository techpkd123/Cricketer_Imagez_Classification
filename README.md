# Cricketer_Imagez_Classification

![image](https://user-images.githubusercontent.com/49801313/118776851-0c936400-b8a6-11eb-9de1-3064b6059697.png)

<table id="classTable">
                        <tbody><tr>
                            <th>Player</th>
                            <th>Probability Score</th>
                        </tr>
                        <tr>
                            <td>Bhuvneshwar Kumar</td>
                            <td id="score_bhuvneshwar_kumar">3.64</td>
                        </tr>
                        <tr>
                            <td>Dinesh Karthik</td>
                            <td id="score_dinesh_karthik">1.72</td>
                        </tr>
                        <tr>
                            <td>Hardik Pandya</td>
                            <td id="score_hardik_pandya">20.17</td>
                        </tr>
                        <tr>
                            <td>Jasprit Bumrah</td>
                            <td id="score_jasprit_bumrah">2.31</td>
                        </tr>
                        <tr>
                            <td>KL Rahul</td>
                            <td id="score_kl_rahul">1.01</td>
                        </tr>
                        <tr>
                            <td>Kedar Jadhav</td>
                            <td id="score_kedar_jadhav">6.19</td>
                        </tr>
                        <tr>
                            <td>Kuldeep Yadav</td>
                            <td id="score_kuldeep_yadav">4.74</td>
                        </tr>
                        <tr>
                            <td>Mohammed Shami</td>
                            <td id="score_mohammed_shami">3.38</td>
                        </tr>
                        <tr>
                            <td>MS Dhoni</td>
                            <td id="score_ms_dhoni">11.79</td>
                        </tr>
                        <tr>
                            <td>Ravindra Jadeja</td>
                            <td id="score_ravindra_jadeja">5.53</td>
                        </tr>
                        <tr>
                            <td>Rohit Sharma</td>
                            <td id="score_rohit_sharma">18.88</td>
                        </tr>
                        <tr>
                            <td>Shikhar Dhawan</td>
                            <td id="score_shikhar_dhawan">2.66</td>
                        </tr>
                        <tr>
                            <td>Vijay Shankar</td>
                            <td id="score_vijay_shankar">1.79</td>
                        </tr>
                           <tr>
                              <td>Virat Kohli</td>
                            <td id="score_virat_kohli">8.6</td>
                        </tr>
                        <tr>
                            <td>Yuzvendra Chahal</td>
                            <td id="score_yuzvendra_chahal">1.94</td>
                        </tr> </tbody></table>
                        <h5>Table:-Output of probablity table<h5>
  <hr>               </hr>
                        
 ![image](https://user-images.githubusercontent.com/49801313/118794599-5df81f00-b8b7-11eb-8245-380fe7b1c7c9.png)
 ![image](https://user-images.githubusercontent.com/49801313/118792834-a9113280-b8b5-11eb-97b1-9349e7a91034.png)
 ![image](https://user-images.githubusercontent.com/49801313/118792998-ce05a580-b8b5-11eb-923f-b272636c64f7.png)
 
 <hr>               </hr>
 
 
 <h3>As seen from above we split the data into train_size(0.25)and test size(0.75) and then fit that into the pipeline after which we get the accuracy as 0.49 which is good          considering the fact we have not used any Neural Networks.After that we caclulate the f1-score for each of the players and we get a f1-score of around (0.3-0.8)range which      is a good one.After that we test the model built different algorithhms like SVM,Logistic Regression and Random Forest Classifier.However finally we conclude that svm and        logistic regression are two of the best contenders for the final algorithm to be chosed.Finally I decided to chose the SVM for further classification purposes because of        the higher score given by it after the testing it with the Y_test and x_test.<h3>


<h2>Installation instructions</h2>
<hr>                     </hr>
<h4>Open project in pyCharm or any IDE</h4> 
<h4>First go to project directory</h4> 
<h4>python3 server.py(Run the program)</h4> 
<h4>Open app.html</h4> 
<h4>And just select an image and click on Classify</h4> 
<h4>After that you can see the results.</h4> 
