# HMHPods
Spec repo for HMH CocoaPods.

## Usage
To use the pods in this repo you will need to add the following to the top of your podfile:

```ruby
source 'https://github.com/theMikeSwan-HMH/HMHPods.git'
```

If you also have public pods in your project you will need to add the default source as well (it only gets added if there are no other sources):

```ruby
source 'https://github.com/CocoaPods/Specs.git'
```

## Pods
### HMHColors 
A library containing all of the official HMH colors from the [2019 Style Guide](https://today.hmhco.com/Documents/HMH_Style_Guide_2019.pdf).

### HMHClassKitHelper
A library for making it easier to work with ClassKit.
