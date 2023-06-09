<script lang ="ts">
    let Arsenal ="https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/800px-Arsenal_FC.svg.png";
    let Aston = "https://upload.wikimedia.org/wikipedia/en/thumb/f/f9/Aston_Villa_FC_crest_%282016%29.svg/800px-Aston_Villa_FC_crest_%282016%29.svg.png";
    let ManCity ="https://upload.wikimedia.org/wikipedia/en/thumb/e/eb/Manchester_City_FC_badge.svg/800px-Manchester_City_FC_badge.svg.png";
    let Newcastle = "https://upload.wikimedia.org/wikipedia/en/thumb/5/56/Newcastle_United_Logo.svg/800px-Newcastle_United_Logo.svg.png";
    let ManUnited = "https://upload.wikimedia.org/wikipedia/en/thumb/7/7a/Manchester_United_FC_crest.svg/800px-Manchester_United_FC_crest.svg.png";
    let Brighton = "https://upload.wikimedia.org/wikipedia/en/thumb/f/fd/Brighton_%26_Hove_Albion_logo.svg/200px-Brighton_%26_Hove_Albion_logo.svg.png";
    let Liverpool = "https://upload.wikimedia.org/wikipedia/en/thumb/0/0c/Liverpool_FC.svg/800px-Liverpool_FC.svg.png";
    let Tottenham = "https://upload.wikimedia.org/wikipedia/en/thumb/b/b4/Tottenham_Hotspur.svg/120px-Tottenham_Hotspur.svg.png";
    let Brentford = "https://upload.wikimedia.org/wikipedia/en/thumb/2/2a/Brentford_FC_crest.svg/800px-Brentford_FC_crest.svg.png";
    let Fullham = " https://upload.wikimedia.org/wikipedia/en/thumb/e/eb/Fulham_FC_%28shield%29.svg/150px-Fulham_FC_%28shield%29.svg.png";
    let Crystal = "https://upload.wikimedia.org/wikipedia/en/thumb/a/a2/Crystal_Palace_FC_logo_%282022%29.svg/800px-Crystal_Palace_FC_logo_%282022%29.svg.png";
    let Chelsea ="https://upload.wikimedia.org/wikipedia/en/thumb/c/cc/Chelsea_FC.svg/190px-Chelsea_FC.svg.png";
    let Wolves = "https://upload.wikimedia.org/wikipedia/en/thumb/f/fc/Wolverhampton_Wanderers.svg/200px-Wolverhampton_Wanderers.svg.png";
    let WHam ="https://upload.wikimedia.org/wikipedia/en/thumb/c/c2/West_Ham_United_FC_logo.svg/175px-West_Ham_United_FC_logo.svg.png";
    let Bornemouth ="https://upload.wikimedia.org/wikipedia/en/thumb/e/e5/AFC_Bournemouth_%282013%29.svg/150px-AFC_Bournemouth_%282013%29.svg.png";
    let Nottingham ="https://upload.wikimedia.org/wikipedia/en/thumb/e/e5/Nottingham_Forest_F.C._logo.svg/110px-Nottingham_Forest_F.C._logo.svg.png";
    let Everton = "https://upload.wikimedia.org/wikipedia/en/thumb/7/7c/Everton_FC_logo.svg/200px-Everton_FC_logo.svg.png";
    let Leichester ="https://upload.wikimedia.org/wikipedia/en/thumb/2/2d/Leicester_City_crest.svg/190px-Leicester_City_crest.svg.png";
    let Leeds ="https://upload.wikimedia.org/wikipedia/en/thumb/5/54/Leeds_United_F.C._logo.svg/160px-Leeds_United_F.C._logo.svg.png";
    let Southampton ="https://upload.wikimedia.org/wikipedia/en/thumb/c/c9/FC_Southampton.svg/180px-FC_Southampton.svg.png";
    let L = "https://scola-smak1bpk.scolacdn.com/users/311245086/content/3.png";
    let D = "https://scola-smak1bpk.scolacdn.com/users/311245086/content/2.png";
    let W = "https://scola-smak1bpk.scolacdn.com/users/311245086/content/1.png";
</script>

<div class = header>
    <a href="/"><img class = "logo" src = "https://a1.espncdn.com/combiner/i?img=%2Fi%2Fleaguelogos%2Fsoccer%2F500%2F23.png"></a>
    <a href="/fixtures">Fixtures</a>
    <a href="/teams">Teams</a>
    <a href="/table">Table</a>

    <a href = "/player">Players</a>
</div>
<div class = "content">
    <div class = "sidebar">  
        <h1>League Table</h1>
        <table>
            <tr>
                <th class="rank">Rank</th>
                <th></th>
                <th>Team</th>
                <th>Played</th>

                <th>GD</th>

                <th>Pts</th>

            </tr>
            <tr>
                <td class="rank">1</td>
                <td><img src={ManCity}></td>
                <td>Manchester City</td>
                <td>38</td>

                <td>+61</td>
   
                <td><b>89</b></td>

            </tr>
            <tr>
                <td class="rank">2</td>
                <td><img src={Arsenal}></td>
                <td>Arsenal</td>
                <td>38</td>

                <td>+45</td>

                <td><b>84</b></td>

            </tr>
            <tr>
                <td class="rank">3</td>
                <td><img src={ManUnited}></td>
                <td>Manchester United</td>
                <td>38</td>

                <td>+15</td>

                <td><b>75</b></td>

            </tr>
            <tr>
                <td class="rank">4</td>
                <td><img src={Newcastle}></td>
                <td>Newcastle</td>
                <td>38</td>

                <td>+34</td>

                <td><b>71</b></td>

            </tr>
            <tr>
                <td class="rank">5</td>
                <td><img src={Liverpool}></td>
                <td>Liverpool</td>
                <td>38</td>

                <td>+28</td>

                <td><b>67</b></td>

            </tr>
            <tr>
                <td class="rank">6</td>
                <td><img src={Brighton}></td>
                <td>Brighton</td>
                <td>38</td>
               

                <td>+19</td>

                <td><b>62</b></td>

            </tr>
            <tr>
                <td class="rank">7</td>
                <td><img src={Aston}></td>
                <td>Aston Villa</td>
                <td>38</td>
               

                <td>+5</td>

                <td><b>61</b></td>

            </tr>
            <tr>
                <td class="rank">8</td>
                <td><img src={Tottenham}></td>
                <td>Tottenham Hotspurs</td>
                <td>38</td>

                <td>+4</td>

                <td><b>57</b></td>

            </tr>
            <tr>
                <td class="rank">9</td>
                <td><img src={Brentford}></td>
                <td>Brentford</td>
                <td>38</td>

                <td>+11</td>

                <td><b>59</b></td>

            </tr>
            <tr>
                <td class="rank">10</td>
                <td><img src={Fullham}></td>
                <td>Fullham</td>
                <td>38</td>

                <td>+2</td>

                <td><b>52</b></td>

            </tr>
            <tr>
                <td class="rank">11</td>
                <td><img src={Crystal}></td>
                <td>Crystal Palace</td>
                <td>38</td>
                <td>-9</td>
                <td><b>45</b></td>

            </tr>
            <tr>
                <td class="rank">12</td>
                <td><img src={Chelsea}></td>
                <td>Chelsea</td>
                <td>38</td>
         
                <td>-9</td>

                <td><b>44</b></td>

            </tr>
            <tr>
                <td class="rank">13</td>
                <td><img src={Wolves}></td>
                <td>Wolves</td>
                <td>38</td>
               
      
                <td>-27</td>

                <td><b>41</b></td>

            </tr>
            <tr>
                <td class="rank">14</td>
                <td><img src={WHam}></td>
                <td>West Ham</td>
                <td>38</td>
              
         
                <td>-13</td>

                <td><b>40</b></td>

            </tr>
            <tr>
                <td class="rank">15</td>
                <td><img src={Bornemouth}></td>
                <td>Bornemouth</td>
                <td>38</td>
               

                <td>-34</td>

                <td><b>39</b></td>

            </tr>
            <tr>
                <td class="rank">16</td>
                <td><img src={Nottingham}></td>
                <td>Nottingham Forest</td>
                <td>38</td>
              

                <td>-30</td>

                <td><b>38</b></td>

            </tr>
            <tr>
                <td class="rank">17</td>
                <td><img src={Everton}></td>
                <td>Everton</td>
                <td>38</td>
              
         
                <td>-23</td>

                <td><b>36</b></td>

            </tr>
            <tr>
                <td class="rank">18</td>
                <td><img src={Leichester}></td>
                <td>Leichester City</td>
                <td>38</td>
            
          
                <td>-17</td>

                <td><b>34</b></td>

            </tr>
            <tr>
                <td class="rank">19</td>
                <td><img src={Leeds}></td>
                <td>Leeds United</td>
                <td>38</td>
           
           
                <td>-30</td>
              
                <td><b>31</b></td>

            </tr>
            <tr>
                <td class="rank">20</td>
                <td><img src={Southampton}></td>
                <td>Southampton</td>
                <td>38</td>
         
                <td>-37</td>
              
                <td><b>25</b></td>

            </tr>
        
        
        </table>
    </div>
    <div class = "main">
    <div class="recent">
        <div class="short-news">
            <h1>MANCHESTER CITY IS CROWNED THE PREMIER LEAGUE 2022/2023 CHAMPIONS</h1>
            <p> Another trophy on the cabinet for Manchester City. An amazing performance for the team that is lead by Josep Guardiola. <br><br> Manchester City is on track for winning the treble. They are in the final of FA Cup and UCL. Provided that they won both of them, this is going to be the second team in EPL to win a treble, after Manchester United in the 1998/1999 season</p>
        </div>
        <div class="thumbnail">
            <img src ="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbFmTCMGigKWyS3tCzmznGNcHwoD-tSKrpsA&usqp=CAU">
        </div>
    </div>
    <div class="other">
        <div class = "news">
            <div class = "head">
                <img src = "https://resources.premierleague.com/photos/premierleague/photo/2023/05/28/921a6ea9-3b1d-41bf-92ec-eceb3f841e89/2023-05-28T173847Z_1871495450_UP1EJ5S1D0K97_RTRMADP_3_SOCCER-ENGLAND-BRE-MCI-REPORT.JPG?width=860&height=573">
            </div>
            <div class = "conten">
                <h1>ERLING HAALAND RECIEVES GOLDEN BOOT AWARD</h1>
                <p>Throughout his sign for Manchester City on summer 2022, Haaland had scored an incredible 36 goals for Manchester City</p>
            </div>
        </div>
        <div class = "news">
            <div class = "head">
                <img src = "https://e3.365dm.com/23/05/768x432/skynews-luton-championship_6170318.jpg">
            </div>
            <div class = "conten">
                <h1>LUTON TOWN AMAZING PROMOTION STORY</h1>
                <p>Luton Town was promoted from non-league division to Premier League in 9 years</p>
            </div>
        </div>
        <div class = "news">
            <div class = "head">
                <img src = "data:image/jpeg;base64,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">
            </div>
            <div class = "conten">
                <h1>3 June 2023: FA Cup Final</h1>
                <p>The FA Cup Final is going to be a Manchester derby match. It is going to be held in Wembley Stadium on the 3rd of June 2023 at 3 P.M UK time.</p>
            </div>
        </div>

    </div>
</div>
</div>
<style>

    .clearfix::after {
         content: "";
         clear: both;
        display: table;
    }

    .short-news{
        color: white;
        background-color:#3f1052;
        padding: 8px;
        text-align: left;
        font-size: fit-content;
        line-height: 1.2;
    }
    .header{
        padding: 16px;
        background-color: #3f1052;
        font-size: 26px;
        align-items: center;
        display: flex;
        width: 100%;

    }
    tr img{
        height: 24px;
        margin-left: auto;
        margin-right: auto;
    }
    .logo{
        height: 80px;
        background-color: white;
        border-radius: 16px;
    }

    .header a{
        color: white;
        text-decoration: none;
        padding-left: 16px;
        padding-right: 16px;
        margin-top: 0px;
    }

    a{
        color: black;
        gap: 16px;
    }

    h1{
        font-size: 24px;
    }

    .recent{
        display: flex;
        flex-direction: row;
        background-color: rgb(255, 238, 191);
        border-radius: 8px;

    }

    .logo{
        height: 80px;
        background-color: white;
        border-radius: 16px;
    }

    .header a{
        color: white;
        text-decoration: none;
        padding-left: 16px;
        padding-right: 16px;
    }

    .content{
        display: flex;
        flex-direction: row;
        width: 100%;
        margin-top:16px;
        margin-left:8px;
        margin-right: 8px; 
        text-align: center;
    }

    .main{
        width: 70%;
        border-radius: 4px;
    }

    .main .short-news{
        width: 30%;
        margin: 8px;
    }
    .thumbnail img{
        width: 100%;
        height: auto;
        top: 50%;
        bottom: 50%;

    }

    .thumbnail{
        max-width: 100%;
        height: auto;
    }

    .sidebar{
        width: 30%;
        margin: 8px;
        background-color: rgb(255, 238, 191);

    }

    table {
        border-collapse: collapse;
        width: 100%;
    }

    table th, table td {
        padding: 8px;
        text-align: left;
        border-bottom: 1px solid #ddd;
    }

    table th {
        background-color: #f2f2f2;
        font-weight: bold;
    }

    table tr:nth-child(even) {
        background-color: #f9f9f9;
    }


    .other{
        display: flex;
        flex-direction: row;
        margin: 16px;
    }

    .news{
        width: 33%;
        display: flex;
        flex-direction: column;
        margin: 4px;
    }

    .news img{
        width: 100%;
        height: 250px;
    }

    .conten{
        display: flex;
        flex-direction: column;
        text-align: left;
    }
</style>