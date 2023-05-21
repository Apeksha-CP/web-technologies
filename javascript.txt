function darkmode(){
    document.body.classList.toggle('dark');
    var toggleButton = document.getElementById('toggle-button');
    if(toggleButton.innerHTML == "Dark Mode"){
        toggleButton.innerHTML = "Light Mode";
    }else{
        toggleButton.innerHTML ="Dark Mode";
    }

    document.getElementById('top').classList.toggle('top-dark');
    document.getElementById('header-content').classList.toggle('header-content-dark');

    const nav = document.getElementsByClassName('a-header');
    for(let i=0;i<nav.length;i++){
        nav[i].classList.toggle('a-header-dark');
    }
    const buttons = document.getElementsByTagName('button');
    for(let i=0;i<buttons.length;i++){
        buttons[i].classList.toggle('button-dark');
    }
    document.getElementById('main-content').classList.toggle('main-content-dark');
    document.getElementById('main-page-intro').classList.toggle('main-page-intro-dark');
    const names = document.getElementsByClassName('name');
    for(let i=0;i<names.length;i++){
        names[i].classList.toggle('name-dark');
    }
    const texts = document.getElementsByClassName('text');
    for(let i=0;i<texts.length;i++){
        texts[i].classList.toggle('text-dark');
    }
    const box = document.getElementsByClassName('threed');
    for(let i=0;i<box.length;i++){
        box[i].classList.toggle('threed-dark');
    }
    const boxheading = document.getElementsByClassName('sk');
    for(let i=0;i<boxheading.length;i++){
        boxheading[i].classList.toggle('sk-dark');
    }
    document.getElementById('skills').classList.toggle('skills-dark');
    document.getElementById('skills-head').classList.toggle('skills-dark');
    
    const headings = document.getElementsByTagName('h1');
    for(let i=0;i<headings.length;i++){
        headings[i].classList.toggle('headings-dark');
    }
    
}