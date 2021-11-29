update & checkout master
`find . -maxdepth 1 -type d \( ! -name . \) -exec bash -c "cd '{}' && git checkout master && git pull &&  pwd" \;`
