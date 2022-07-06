# {{ cookiecutter.project_name }}
This is a great README file by {{ cookiecutter.author }}
({{ cookiecutter.email }})

The project is about:
{{ cookiecutter.description }}

## Team:
{% if cookiecutter.project_team == 'Meta 1' %}
* Coordenador: Wandemberg Santana (wandemberg.gibaut@eldorado.org.br)
* Especialista Android: Felipe Augusto (felipe.augusto@eldorado.org.br)
* Daniel Miranda (daniel.miranda@eldorado.org.br)

{% elif cookiecutter.project_team == 'Meta 2' %}
* Coordenador: Wandemberg Santana (wandemberg.gibaut@eldorado.org.br)
* Especialista Android: Felipe Augusto (felipe.augusto@eldorado.org.br)
* Especialista Android: Daniel Miranda (daniel.miranda@eldorado.org.br)


{% elif cookiecutter.project_team == 'Meta 3' %}
* Coordenador: Alexandre Osório (alexandre.osorio@eldorado.org.br)
* Especialista Android: Felipe Augusto (felipe.augusto@eldorado.org.br)
* Especialista Android: Daniel Miranda (daniel.miranda@eldorado.org.br)

{% elif cookiecutter.project_team == 'Meta 4' %}
* Coordenador: Amparo Munoz (amparo.munoz@eldorado.org.br)
* Especialista Android: Felipe Augusto (felipe.augusto@eldorado.org.br)
* Especialista Android: Daniel Miranda (daniel.miranda@eldorado.org.br)

{% elif cookiecutter.project_team == 'Meta 5' %}
* Coordenador: Sildolfo Gomes (amparo.munoz@eldorado.org.br)
* Especialista Android: Felipe Augusto (felipe.augusto@eldorado.org.br)
* Especialista Android: Daniel Miranda (daniel.miranda@eldorado.org.br)

{% elif cookiecutter.project_team == 'Meta 6' %}
* Coordenador(es): Alexandre Osorio, Amparo Munoz, Sildolfo Gomes, Wandemberg Santana
* Especialista Android: Felipe Augusto (felipe.augusto@eldorado.org.br)
* Especialista Android: Daniel Miranda (daniel.miranda@eldorado.org.br)
{% endif %}