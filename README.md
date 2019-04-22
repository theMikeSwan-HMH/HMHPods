# HMHPods
Spec repo for HMH CocoaPods.

## Usage
To use the pods in this repo you will need to add the following to the top of your podfile:

```ruby
source ''
```

If you also have public pods in your project you will need to add the default source as well (it only gets added if there are no other sources):

```ruby
source 'https://github.com/CocoaPods/Specs.git'
```
