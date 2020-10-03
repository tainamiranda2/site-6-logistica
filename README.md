/* Menu responsivo tags adcionada no javaScript */
    .nav-mobile {
        display: none;
        cursor:  pointer;
        position: absolute;
        top:  0;
        left: 0;
        background: #ffc600;
        border-radius: 5px;
        line-height: 50px;
        width: 100%;
        height: 50px;
    } 
        .nav-mobile:after {
            content: "↓ ABRIR MENU";
        }

    .nav-active {
        display: block !important;
        margin-top: 50px;
    }

    .nav-mobile-open {
        border-radius: 5px 5px 0 0;
    }
        .nav-mobile-open:after {
            content:  "↑ FECHAR MENU";
        }

/* Menu responsivo */
@media (max-width: 480px) {
    .nav-item:first-child a {
        border-radius: 0 !important;
    }
}

@media (min-width: 480px) {
    
    .nav-mobile {
        left: 50%;
        width: 300px;
        margin-left: -150px;
    }

    .nav-item:first-child a {
        border-radius: 5px 0 0 5px;
    }
}

@media (max-width: 768px) {
    .nav {
        font-size: 5vw;
        min-height: 50px;
    }
        .nav-list {
            width: 100%;
            display: none;
        }
            .nav-item {
                width: 100%;
                float: none;
                border-top:  1px solid #FFCF00;
            }
                .nav-item:first-child a {
                    border-radius: 5px 5px 0 0;
                }

                .nav-item:last-child a {
                    border-radius: 0 0 5px 5px;
                }

    /*Deixa o menu mobile visivel só para celulares e tablets */
    .nav-mobile {
        display: block;
    }
}



#principal {
    margin-top:  30px;
}
    #principal p {
        font-size: 3.5vw;
        margin-top: 20px;
    }
        @media (min-width: 768px) {
            #principal p {
                font-size: 1.6vw;
            }
        }
        