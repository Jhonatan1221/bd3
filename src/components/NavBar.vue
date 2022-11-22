<template>
    <div>
        <nav>
            <div class="nav-wrapper light-blue">
                <routerLink to="/" class="brand-logo">Proyectos</routerLink>
                <a href="#" data-target="mobile-demo" class="sidenav-trigger"><i class="material-icons">menu</i></a>
                <ul class="right hide-on-med-and-down">
                 <li>
                    <routerLink to="/home">Home</routerLink>
                 </li> 
                 <li>
                    <routerLink to="/about">About</routerLink>
                 </li> 
                 <li>
                    <routerLink to="/proyectos" class="waves-effect waves-light btn red lighten">Proyectos</routerLink>
                 </li> 
                </ul>
            </div>
        </nav>

        <ul class="sidenav" id="mobile-demo">
            <li>
                <routerLink to="/home">Home</routerLink>
            </li> 
            <li>
                <routerLink to="/about">About</routerLink>
            </li>   
            <li>
                <routerLink to="/proyectos">Proyectos</routerLink>
            </li> 
        </ul>

    </div>
</template>

<script>
export default {
    mounted(){
        M.AutoInit();
    },
};
</script>