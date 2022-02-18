## ansible-cran light

This is repo is a stripped down fork of the original version that gets rid of the ansible-galaxy installation / deployment
necessity. Hence the repo is a bit more playing around friendly. Plus it is more focused on providing an idea for actual CRAN R packages that should be part of a real data & analytics engineering playbook. 

Just run

```
ansible-playbook --module-path=library r-pack-plays.yml
```

in the document root of the repository (assuming ansible is installed). 



## Acknowledgements 

Thanks to [yutannihilation](https://github.com/yutannihilation) for the original ansible module. 
This repository is just a stripped down fork of the original version. 


## License


MIT
