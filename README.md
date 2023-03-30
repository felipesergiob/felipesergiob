 Hi there 👋

class Developer {
  final String username;
  final String name;
  final String email;
  final List<String> social;
  final Map<String, dynamic> code;

  Developer()
      : username = 'felipesergiob',
        name = 'Felipe Sérgio Barroso',
        email = 'felipessmbf@gmail.com',
        social = [
          'https://toshiossada.dev/',
          'https://www.linkedin.com/in/toshiossada/',
          'https://toshiossada.medium.com/',
          'https://instagram.com/toshiossada',
          'https://www.facebook.com/ToshiOssada/',
        ],
        code = {
          'mobile': ['Flutter'],
          'frontend': ['Flutter', 'HTML', 'CSS', 'JavaScript'],
          'tools': [
            'GIT',
            'GitHub',
          ],
          'misc': ['Firebase']
        };
}
