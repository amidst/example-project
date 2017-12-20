# AMIDST Example project


git clone https://github.com/amidst/example-project.git

mvn clean package

java -cp target/example-project-full.jar BasicExample


git verify-pack -v .git/objects/pack/pack-9682457152606a8428c0710b12e217d363082685.pack | tail -n 100 | cat > pack-9682457152606a8428c0710b12e217d363082685.pack_new