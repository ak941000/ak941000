body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(to right, #f7b501,#e0e0e0, #088619 );
    background-size: 600% 600%;
    animation: gradientAnimation 7s ease infinite;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

.header {
    background-color: #f4f4f4;
    color: #333;
    box-shadow: 0 2px 10px rgba(120, 23, 60, 0.6);
    
    padding: 20px 0;
    text-align: center;
    position: relative;
}

.icons {
    position: absolute;
    top: 20px;
    right: 20px;
}

.icon {
    display: inline-block;
    margin: 0 5px;
}

.icon.login {
    background-color: black;
    color: white;
    padding: 5px 10px;
    border-radius: 5px;
}

.team-name {
    font-weight: bold;
}

.info-section {
    box-shadow: 0 2px 10px rgba(95, 88, 90, 0.6);
    display: flex;
    justify-content: space-around;
    margin: 20px 0;
}

.info-box {
    background-color: #dfe4ea;
    border-radius: 5px;
    padding: 20px;
    text-align: center;
    width: 30%;
}

.info-value {
    font-size: 24px;
    margin-top: 10px;
}

.content-section {
    box-shadow: 0 2px 10px rgba(95, 88, 90, 0.6);
    display: flex;
    justify-content: space-around;
    margin-bottom: 20px;
}

.working-time,
.bar-chart {
    background-color: #dfe4ea;
    border-radius: 5px;
    padding: 20px;
    width: 45%;
}

.time-graph {
    width: 100px;
    height: 100px;
    background-color: black;
    border-radius: 50%;
    margin: auto;
}

.bar-chart canvas {
    width: 100%;
}
@keyframes gradientAnimation 
{
    0% { background-position: 0% 0%; }
    50% { background-position: 100% 100%; }
    100% { background-position: 0% 0%; }
}
