node {
checkout scm
stage('kopiuj'){

sh 'ssh pk@localhost mkdir koniec'
sh 'ssh pk@localhost git clone git://github.com/yegalut/projekt koniec'

}

stage('uruchom dockera'){sh 'ssh pk@localhost docker-compose -f koniec/docker-compose.yml up -d'
}
}
