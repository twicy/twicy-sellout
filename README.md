# twicy-sellout
The last block:

vgg_BN.load_state_dict(torch.load('./weights/MiniVGG-BN.pth'))
test(vgg_BN, dataloaders['test'])

is not working