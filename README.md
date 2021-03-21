# CSS Concepts

Notes :

Grid

    > align-content : To align track vertically
    > justify-content : To align track horizontally

    > align-items : To align items vertically
    > justify-items : To align items horizontally

    > auto-fill : create extra track
    > auto-fit : does not create extra track
    eg: grid-template-columns: repeat(auto-fit, minmax(150px, 1fr))

Flexbox

    > justify-content : Align Content horizontally
    > align-items : Align Items vertically

    When, flex-direction : row    -> -----------------main axis     justify-content works hortizontally
                                           |                        align-content works vertically
                                           |                        (works only when there is wrapped items
                                           |                         to 2nd or 3rd row or so on...)
                                           |          cross axis    align-items works vertically
                                           |
                                           |

    When, flex-direction : column ->       |
                                           |
                                           |          main axis     justify-content works vertically
                                           |
                                           |
                                    ----------------- cross axis    align-items works horizontally
