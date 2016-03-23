# Running Desktop Containers on Mac OSX


#Prerequisites:

- [brew](http://brew.sh/)
- [xquartz](http://www.xquartz.org/)

#Installation

Install brew
````
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
````

Install brew
````
brew install xquartz
````

Add this to your .bash_profile
````

for file in ~/.{dockerfunc}; do
	[[ -r "$file" ]] && [[ -f "$file" ]] && source "$file"
done
unset file

````

Then add ````.dockerfunc```` to you $HOME