
<div class = header>
    <a href="/"><img class = "logo" src = "https://a1.espncdn.com/combiner/i?img=%2Fi%2Fleaguelogos%2Fsoccer%2F500%2F23.png"></a>
    <a href="/fixtures">Fixtures</a>
    <a href="/teams">Teams</a>
    <a href="/table">Table</a>

    <a href = "/player">Players</a>
</div>


<script lang="ts">

    const clubs = [
    {
        name: "Arsenal",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Arsenal_FC.svg/800px-Arsenal_FC.svg.png",
        background: "https://lh3.googleusercontent.com/p/AF1QipNBQS1ym3o-5wktmc6wtxWu8To23nLySY9nW_6N=s680-w680-h510",
        stadium: "Emirates Stadium",
        website: "https://www.arsenal.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Aston Villa",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/f/f9/Aston_Villa_FC_crest_%282016%29.svg/800px-Aston_Villa_FC_crest_%282016%29.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/0/01/Villa_Park.jpg",
        stadium: "Villa Park",
        website: "https://www.avfc.co.uk/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "AFC Bornemouth",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/e/e5/AFC_Bournemouth_%282013%29.svg/800px-AFC_Bournemouth_%282013%29.svg.png",
        background: "https://images-morebus.passenger-website.com/Untitled%20design%20%2810%29.png",
        stadium: "Vitality Stadium",
        website: "https://www.afcb.co.uk/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Brentford",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/2/2a/Brentford_FC_crest.svg/800px-Brentford_FC_crest.svg.png",
        background: "https://res.cloudinary.com/brentford-fc/image/upload/f_auto,q_auto:best,f_auto,c_fill,ar_16:9/Production/w-1237_h-auto_m-fit_s-any__Pitch_Screen_5_ExileNationLogo_fdyva2.jpg",
        stadium: "Gtech Community Stadium",
        website: "https://www.brentfordfc.com/en??utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Brighton",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/f/fd/Brighton_%26_Hove_Albion_logo.svg/800px-Brighton_%26_Hove_Albion_logo.svg.png",
        background: "https://resources.brightonandhovealbion.com/photo-resources/2022/09/12/bd9eaa24-0d2c-445e-9751-2effbfb4684e/Brighton_-_Hove_Albion_v_Leicester_City_04SEP22_PH.250.JPG?width=840",
        stadium: "Amex Stadium",
        website:"https://www.brightonandhovealbion.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Chelsea",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/c/cc/Chelsea_FC.svg/800px-Chelsea_FC.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Stamford_Bridge_Clear_Skies.JPG/1200px-Stamford_Bridge_Clear_Skies.JPG",
        stadium: "Stamford Bridge",
        website: "https://www.chelseafc.com/en??utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Crystal Palace",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/a/a2/Crystal_Palace_FC_logo_%282022%29.svg/800px-Crystal_Palace_FC_logo_%282022%29.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/Selhurst_Park_Holmesdale_Stand.jpg/250px-Selhurst_Park_Holmesdale_Stand.jpg",
        stadium: "Selhurst Park",
        website:"https://www.cpfc.co.uk/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Everton",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/7/7c/Everton_FC_logo.svg/800px-Everton_FC_logo.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/8/88/Goodison_Park%2C_October_2021.jpg/300px-Goodison_Park%2C_October_2021.jpg",
        stadium: "Goodison Park",
        website:"https://www.evertonfc.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Fullham",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/e/eb/Fulham_FC_%28shield%29.svg/800px-Fulham_FC_%28shield%29.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/7/75/Craven_Cottage_Football_Ground_-_geograph.org.uk_-_778731.jpg",
        stadium: "Craven Cottage",
        website:"https://www.fulhamfc.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Leeds United",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/5/54/Leeds_United_F.C._logo.svg/800px-Leeds_United_F.C._logo.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/Leeds_United_-_31559864360.jpg/250px-Leeds_United_-_31559864360.jpg",
        stadium: "Elland Road",
        website: "https://www.leedsunited.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Leichester City",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/2/2d/Leicester_City_crest.svg/800px-Leicester_City_crest.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/b/bb/King_Power_Stadium_wide_view.jpg/300px-King_Power_Stadium_wide_view.jpg",
        stadium: "King Power Stadium",
        website: "https://www.lcfc.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link&lang=en"
    },
    {
        name: "Liverpool",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/0/0c/Liverpool_FC.svg/800px-Liverpool_FC.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/0/02/Panorama_of_Anfield_with_new_main_stand_%2829676137824%29.jpg/1280px-Panorama_of_Anfield_with_new_main_stand_%2829676137824%29.jpg",
        stadium: "Anfield",
        website: "https://www.liverpoolfc.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Manchester City",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/e/eb/Manchester_City_FC_badge.svg/800px-Manchester_City_FC_badge.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/b/b8/Etihad_Stadium.jpg/300px-Etihad_Stadium.jpg",
        stadium: "Etihad Stadium",
        website: "https://www.mancity.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Manchester United",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/7/7a/Manchester_United_FC_crest.svg/800px-Manchester_United_FC_crest.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/3/33/Manchester_United_Panorama_%288051523746%29.jpg/1920px-Manchester_United_Panorama_%288051523746%29.jpg",
        stadium: "Old Trafford",
        website:"https://www.manutd.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Newcastle United",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/5/56/Newcastle_United_Logo.svg/800px-Newcastle_United_Logo.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/SJP-NUFCvMUFC%2827_Dec_21%29.jpg/1024px-SJP-NUFCvMUFC%2827_Dec_21%29.jpg",
        stadium: "Saint James Park",
        website:"https://www.nufc.co.uk/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Nottingham Forest",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/e/e5/Nottingham_Forest_F.C._logo.svg/800px-Nottingham_Forest_F.C._logo.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/Panoramara2.JPG/1920px-Panoramara2.JPG",
        stadium: "City Ground",
        website: "https://www.nottinghamforest.co.uk/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Southampton",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/c/c9/FC_Southampton.svg/800px-FC_Southampton.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/5/52/St_Mary%27s_Stadium_%282%29.jpg",
        stadium: "Saint Mary Stadium",
        website:"https://www.southamptonfc.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "Tottenham Hotspur",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/b/b4/Tottenham_Hotspur.svg/800px-Tottenham_Hotspur.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/b/be/London_Tottenham_Hotspur_Stadium.jpg/1024px-London_Tottenham_Hotspur_Stadium.jpg",
        stadium: "Tottenham Hotspur Stadium",
        website: "https://www.tottenhamhotspur.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    {
        name: "West Ham United",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/c/c2/West_Ham_United_FC_logo.svg/800px-West_Ham_United_FC_logo.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/London_Olympic_Stadium_West_Ham.jpg/1024px-London_Olympic_Stadium_West_Ham.jpg",
        stadium: "London Stadium",
        website:"https://www.whufc.com/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"

    },
    {
        name: "Wolventon Wanderers",
        image: "https://upload.wikimedia.org/wikipedia/en/thumb/f/fc/Wolverhampton_Wanderers.svg/800px-Wolverhampton_Wanderers.svg.png",
        background: "https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/MolineuxStadium2022.jpg/1024px-MolineuxStadium2022.jpg",
        stadium: "Molineux Stadium",
        website:"https://www.wolves.co.uk/?utm_source=premier-league-website&utm_campaign=website&utm_medium=link"
    },
    ];
 </script>

<div class="grid-container">
{#each clubs as club}
    <div class="club">
    <a href={club.website}><div class="club">
      <div class="identity">
        <img src={club.image} alt={club.name} />
      <b>{club.name}</b>
      {club.stadium}
      </div>
    </div>
</div>
{/each}
</div>

<style>
:global(*) {
  margin: 0;
  padding: 0;
}

background-image{
    background-repeat:no-repeat;
}

img {
  object-fit: contain;
    max-width: 100%;
    }


.grid-container {
  display: grid;
  grid-template-columns: repeat(5, minmax(0, 1fr));
  gap: 16px;
  padding: 16px;
  background-size: cover;
  background-repeat: no-repeat;
}
.club{
    display: flex;
    flex-direction: column;
    text-align: center;
    border-radius: 25px;
    height: 256px;
    padding: 8px;
}


.club img{
    height: 128px;
    padding: 16px;
}

.identity{
    display: flex;
    flex-direction: column;
    background-color: rgba(226, 125, 112, 0.925);
    font-size: 12px;
    border-radius: 25px;
}

.identity b{
    font-size: 20px;
}
.header{
        padding: 16px;
        background-color: #3f1052;
        font-size: 36px;
        align-items: center;
        display: flex;


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

    a{
        color: black;
        text-decoration: none;
    }
</style>