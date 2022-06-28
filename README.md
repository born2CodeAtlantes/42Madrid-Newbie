# Welcome back, traveler.
Hola, viajero [ [espacial ]], es posible que te haya tragado un Black Hole y has acabado en otro universo después de un tiempo, o probablemente me equivoco y vengas de cierto lugar [[ acuático ]].
De igual manera, quizá prefieras ciertos consejos [[ personales ]] para ponerte un poco mas comod@.
# Time to be a BIG SHOT (within the rules).
Quizá no venga mal repasar las [guías de convivencia y del edificio](https://github.com/42MadridFT/Guia).
Les falta una [[ actualización ]] en algunos puntos, pero te puedes hacer la idea general.
## From zero to hero (or not).
Nuevamente, mi recomendación personal, pero muchas personas o bien tendrán el escritorio lleno de [[ INFORMACION REDACTADA ]], o tendrán muchas aplicaciones antiguas que ya no sirven o están deprecadas. Te recomiendo que hagas una copia de seguridad ya sea a través de GitHub o a través de goinfre (en general mejor GitHub, ya deberías estar subiendo tus proyectos a un repositorio personal privado) y hacer un reset a tu usuario. Para ello, abre una terminal y pon
> touch ~/.reset
Obviamente esto es completamente opcional y no tienes por que hacerlo, pero es una opción cuando te empiece a dar problemas el Mac por falta de espacio.
## Toqueteando la terminal
Abre iterm2 y arriba en el menú contextual:
Profiles > Open Profiles > Edit Profiles > Window > Window Columns and Rows
Yo recomiendo personalmente 150C 40R, porque las ventanas por defecto son demasiado [[ pequeñas ]].
Quizá prefieras también instalar Oh my Zsh
> sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)”
Y, si lo has hecho, instalar el popular tema powerlevel10k.
> git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
> nano ~/.zshrc
Edita ZSH_THEME de manera que quede así
>ZSH_THEME="powerlevel10k/powerlevel10k"
Guarda con Ctrl + X y seguidamente para aplicar los cambios:
> source ~/.zshrc
Ahora configura powerlevel10k a tu gusto. Te recomiendo que instales las fuentes que te piden.
Congratulations, ya tienes la terminal relativamente bonita!
## Workflow
Para trabajar en 42 supongo que ya tienes preparado el Slack, pero si no te recomiendo que lo pongas tanto en el mac como en tus dispositivos móviles y te conectes al espacio de trabajo de 42born2code(.slack.com).
Ahí se anuncian todas las noticias de 42, además de que es el sitio donde preferiblemente debes reportar problemas o dar tus aportaciones.
Después de Slack lo normal es instalar VSCode (a no ser de que seas uno de esos psicópatas que gustan de VIM). Con VSCode
> `{`
"Comentario": {
"prefix": `**"**``comment42``**"**``,`
"body": [
`**"**``/*``**"**``,`
`**"**``** * DESCRIPTION``**"**``,`
`**"**``** Description of function``**"**``,`
`**"**``** * @param myParam``**"**``,`
`**"**``** Description of params``**"**``,`
`**"**``** * RETURN VALUE``**"**``,`
`**"**``** Explain what do you return``**"**``,`
`**"**``*/``**"**`
`],`
`"description":` `**"**``Comentario``**"**`
`}`
`}`
