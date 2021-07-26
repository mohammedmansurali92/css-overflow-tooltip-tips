# css-overflow-tooltip-tips
css overflow tooltip tips
<style>
       div{
           width: 100px;
           height: 250px;
           background-color: darkgreen;
           border: 1px solid red;
           overflow:scroll;
       }
       .tooltip:hover .tooltip-text{
           visibility: visible;
       }
       .tooltip{
           position:relative;
       }
       .tooltip .tooltip-text{
         visibility: hidden;
        background-color: brown;
        color: white;
        padding: 10px;
        border-radius: 5px;
        position: absolute;
        top:30px;
        left:30px;
        z-index: 1;

       }
        </style>
</head>
<body>
    <a href="#" class="tooltip">
      Facebook
      <span class="tooltip-text">This is a facebook page</span>
    </a>
    <br/><br/>
    <div>
       Stet clita sadipscing nonumy invidunt justo dolore. Amet eirmod stet amet sed rebum dolore erat et, rebum lorem accusam et diam et erat, consetetur elitr sed et sit. Aliquyam gubergren dolor erat et. Eirmod voluptua lorem eos est erat sit tempor et, ea sed sit magna dolor dolores. Rebum stet. 
    </div>
   
</body>
