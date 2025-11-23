#include <iostream>
#include <string>
#include <random>
#include <ctime>
#include <vector>
#include <algorithm>
#include <cstdlib>

using namespace std;

string GeneratePassword()
{
    const string  up ="QWVXDJKGOP0TH";
    const string lower ="owroptuiidghjkzvbx";
    const string digits = "1234567890";
    const string symb = "#/$@$";
    const string all = up + lower + digits + symb;

    vector <char> password;

    password.push_back(up[rand () % up.size()]);
    password.push_back(digits[rand () % digits.size()]);
    password.push_back(symb[rand () % symb.size()]);

    
    int length = 5 + rand() % 5; 
    for (int i = 3; i < length; ++i) {
        password.push_back(all[rand() % all.size()]); 
    }

    return string(password.begin(), password.end());
}

void start() {

    int count;
   

        std::cout << "_____  _____ _   _ ______  ___ _____ ___________           " << endl;
        std::cout << "|  __ \\|  ___| \\ | || ___ \\/ _ \\_   _|  _  | ___ \\          " << endl;
        std::cout << "| |  \\/| |__ |  \\| || |_/ / /_\\ \\| | | | | | |_/ /          " << endl;
        std::cout << "| | __ |  __|| . ` ||    /|  _  || | | | | |    /           " << endl;
        std::cout << "| |_\\ \\| |___| |\\  || |\\ \\| | | || | \\ \\_/ / |\\ \\           " << endl;
        std::cout << " \\____/\\____/\\_| \\_/\\_| \\_\\_| |_/\\_/  \\___/\\_| \\_|          " << endl;
        std::cout << "                                                            " << endl;
        std::cout << "                                                            " << endl;
        std::cout << "______  ___   _____ _____  _    _  _________________  _____ " << endl;
        std::cout << "| ___ \\/ _ \\ /  ___/  ___|| |  | ||  _  | ___ \\  _  \\/  ___|" << endl;
        std::cout << "| |_/ / /_\\ \\\\ `--.\\ `--. | |  | || | | | |_/ / | | |\\ `--. " << endl;
        std::cout << "|  __/|  _  | `--. \\`--. \\| |/\\| || | | |    /| | | | `--. \\" << endl;
        std::cout << "| |   | | | |/\\__/ /\\__/ /\\  /\\  /\\ \\_/ / |\\ \\| |/ / /\\__/ /" << endl;
        std::cout << "\\_|   \\_| |_/\\____/\\____/  \\/  \\/  \\___/\\_| \\_|___/  \\____/ " << endl;
        std::cout << "                                                            " << endl;
        std::cout << "                                                            " << endl;

  
        std::cout << " How much password generated > ";
        std::cin >> count;
    vector <string> passwords; 
    std::cout << " YOU PASSWORDS :  ";

    for (int i = 0; i < count + 1; ++i) {
        passwords.push_back(GeneratePassword());
    }

    for (int i = 1; i < count + 1; ++i) {
        std::cout << i << ") " << passwords.at(i) << endl;
      
    }

    system("pause > 0");
}
int main()
{
    srand(time(0)); 
    start(); 
}
