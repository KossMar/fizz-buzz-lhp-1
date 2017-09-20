# fizz-buzz-lhp-1
Lighthouse Prep Assignment 1

#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    @autoreleasepool {
        
        for (int x = 0; x <= 100; x++){
            if (x % 3 == 0 && x % 5 == 0){
                NSLog(@"FizzBuzz");
                continue;
            }
            else if (x % 3 == 0) {
                NSLog(@"Fizz");
                continue;
            }
            else if (x % 5 == 0) {
                NSLog(@"Buzz");
                continue;
            }
            else {
                NSLog(@"%d", x);
            }
        
    }
}
    return 0;
}
