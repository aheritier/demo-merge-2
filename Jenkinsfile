node {
  checkout scm

  def a = readFile 'A.txt'
  def b = readFile 'B.txt'

  echo "a: ${a}"
  echo "b: ${b}"

  if ( a.toInteger() >= b.toInteger() ) {
    error 'A is greater than B'
  }
}

